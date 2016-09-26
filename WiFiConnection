#WiFi.status

Retrieve the current WiFi status.
wl_status_t status()
The status returned will be one of:

අපි WIFI  එකට සම්බන්ද වනවිට පහත සදහන් return පරික්ෂා  කිරීම 
මගින්  නැවත සම්බන්දතාව අවශ්‍යද යනවග නිරීක්ෂණය කල  හැක .


• WL_IDLE_STATUS (0)
• WL_NO_SSID_AVAIL (1)
• WL_SCAN_COMPLETED (2)
• WL_CONNECTED (3)



තවද පහත සදහන් ක්‍රමය මගින් ද සම්බන්දතාව නිරීක්ෂණය කල හැක 
uint8_t waitForConnectResult() 

නමුත් පහත සදහන් ක්‍රියාව මගින් return  වනුවේ 
WL_DISCONNECTED එම නිසා වැඩ ප්‍රයෝගික ක්‍රමය වනුවේ 
පහත ආකාරයටය 

වඩාත් උචිත ක්‍රම වේදය වනුවේ 

while (WiFi.status() != WL_CONNECTED) {
delay(500);
Serial.print(".");
}

තවද පහත සදහන් library එක නිවැරදිව සදහන් කල යුතිය   

ESP8266WiFi.h
