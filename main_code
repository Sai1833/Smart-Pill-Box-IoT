#include <WiFi.h> 
#include <WebServer.h> 
const char* ssid = "YOUR_WIFI_NAME"; 
const char* password = "YOUR_WIFI_PASSWORD"; 
WebServer server(80); 
const int buttonPins[16] = {32, 33, 25, 26, 27, 14, 12, 13, 23, 22, 21, 19, 18, 5, 4, 15}; 
void handleRoot() { 
String message = "Pill Box Status:\n\n"; 
for (int i = 0; i < 16; i++) { 
bool isTaken = digitalRead(buttonPins[i]) == HIGH;  
message += "Slot " + String(i + 1) + ": " + (isTaken ? "TAKEN" : "REPLACED") + "\n"; 
} 
server.send(200, "text/plain", message); 
} 
void setup() { 
Serial.begin(115200); 
for (int i = 0; i < 16; i++) pinMode(buttonPins[i], INPUT_PULLUP); 
WiFi.begin(ssid, password); 
while (WiFi.status() != WL_CONNECTED) { delay(500); Serial.print("."); } 
Serial.println("\nConnected! IP: " + WiFi.localIP().toString()); 
server.on("/", handleRoot); 
server.begin(); 
} 
void loop() { 
server.handleClient(); 
}
