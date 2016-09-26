#WiFiClient

WiFiClient.available () : Return the amount of data available to be read.

int available() :Return the amount of data available to be read.

##WiFiClient.connect()

Connect to the given host at the given port using TCP.

int connect(const char* host, uint16_t port)

int connect(IPAddress ip, uint16_t port)

-Example :

WiFiClient client;
  const int httpPort = 80;
  if (!client.connect(host, httpPort)) {
    Serial.println("connection failed");
    return;
  }

Connect to the given host at the given port using TCP. This function returns 0 on a failure.
WiFiClient.connected
Determine if we are connected to a partner.
uint8_t connected()
Return true if connected and false otherwise.
WiFiClient.flush
void flush()
WiFiClient.getNoDelay
bool getNoDelay()
WiFiClient.peek
int peek()
WiFiClient.read
Read data from the partner.
int read()
int read(uint8_t *buf, size_t size)
Read data from the partner. These functions read either a single byte or a sequence of bytes from
the partner.
WiFiClient.remoteIP
Retrieve the remote IP address of the connection.
IPAddress remoteIP()
Retrieve the remote IP address of the connection.
Page 224WiFiClient.remotePort
Return the remote port being used in an existing connection.
uint16_t remotePort()
Return the remote port being used in an existing connection.
WiFiClient.setLocalPortStart
Set the initial port for allocating local ports for connections.
void setLocalPortStart(uint16_t port)
Set the initial port for allocating local ports for connections.
WiFiClient.setNoDelay
void setNoDelay(bool nodelay)
WiFiClient.status
uint8_t status()
WiFiClient.stop
Disconnect a client.
void stop()
Disconnect a client.
WiFiClient.stopAll
Stop all the connections formed by this WiFi client.
void stopAll()
WiFiClient.write
Write data to the partner.
size_t write(uint8_t b)
size_t write(const uint8_t *buf, size_t size)
size_t write(T& source, size_t unitSize);
Write data to the partner. The first function writes one byte, while the second function writes an
array of characters.
