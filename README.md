# ⚡ SpeedSGM

### A modern, powerful GUI network benchmarking and speed-testing application powered by iperf3.

SpeedSGM is a modern network performance testing application built around the industry-standard **iperf3** network testing engine.

It provides a polished graphical interface for performing real network benchmarks, monitoring live throughput, testing different protocols and directions, discovering public iperf3 servers, tracking data consumption, and running long-duration network stress tests.

Instead of hiding the networking engine behind a simple "Start Test" button, SpeedSGM exposes the important controls while keeping the experience simple enough for everyday testing.

---

## 🚀 Features

### 🌐 Real Network Benchmarking

SpeedSGM performs actual network tests using the iperf3 engine.

It supports:

- TCP
- UDP
- SCTP
- Upload testing
- Download testing
- Bidirectional testing
- Parallel streams
- Custom bandwidth targets
- Custom test duration
- Continuous / forever testing
- Custom reporting intervals
- IPv4
- IPv6
- Custom ports
- JSON output
- Real-time statistics

This means SpeedSGM is not a simulated speed meter.

It generates and measures real network traffic.

---

# ⚡ Speed Testing

Run a test against any compatible iperf3 server.

Configure:

- Protocol
- Direction
- Bandwidth
- Duration
- Port
- Number of parallel streams
- Reporting interval
- IP version

Then start the test and watch the connection in real time.

### Supported directions

**Download**

The remote iperf3 server sends traffic to your device.

**Upload**

Your device sends traffic to the remote iperf3 server.

**Both Directions**

Traffic is transmitted in both directions simultaneously.

---

# 🧪 TCP / UDP / SCTP

SpeedSGM supports multiple iperf3 protocols.

### TCP

Useful for measuring practical TCP throughput and observing how the connection behaves under sustained traffic.

### UDP

Useful for testing:

- Throughput
- Jitter
- Packet loss
- Datagram behavior
- Network stability

UDP bandwidth can be configured manually, allowing controlled high-load testing.

### SCTP

SCTP is also supported for environments where SCTP testing is required.

---

# 🏆 Find The Best Server

SpeedSGM includes an automatic server discovery system.

The application can retrieve available public iperf3 servers and test candidate servers to find a low-latency option.

The process can:

1. Retrieve the server list
2. Filter available candidates
3. Test server connectivity
4. Measure latency
5. Compare candidates
6. Select a suitable server
7. Automatically populate the server and port

No need to manually search through hundreds of servers.

---

# 🌍 Live Public Server List

SpeedSGM can retrieve public iperf3 server information from the public iperf3 server registry.

The server list can contain information such as:

- Host
- IP address
- Port
- Provider
- Country
- Continent
- Website
- Capacity
- Availability

The server selector includes:

- Search
- Sorting
- Server selection
- Port information
- Provider information
- Geographic information

---

# 📊 Real-Time Speed Graph

SpeedSGM provides a live network throughput graph while a test is running.

The graph displays:

- Download speed
- Upload speed
- Current throughput
- Peak throughput
- Historical measurements

The graph updates continuously as iperf3 reports new measurements.

---

# 📈 Live Speed Monitoring

Large live speed indicators make it easy to see what's happening during a test.

SpeedSGM tracks:

- Current download speed
- Current upload speed
- Peak download speed
- Peak upload speed
- Final test results

Units are automatically displayed based on the measured throughput.

---

# 🖥️ Built-In Terminal

SpeedSGM includes a live terminal/log panel.

Instead of hiding the iperf3 output, the application exposes it in a readable interface.

The terminal provides:

- Timestamped output
- Real-time iperf3 logs
- Executed command visibility
- Connection information
- Interval results
- Error messages
- Test status
- Automatic scrolling

This makes diagnosing failed connections much easier.

---

# 📡 Data Usage Tracking

SpeedSGM tracks the amount of data generated during testing.

The data page can display:

- Download data
- Upload data
- Total data
- Persistent usage totals

Usage information can persist between application sessions.

A dedicated **Clear Data** function allows the recorded totals to be reset.

This is especially useful when running long-duration tests.

---

# ♾️ Forever Mode

SpeedSGM supports continuous testing.

Instead of limiting a test to a few seconds, users can run a test continuously until manually stopped.

Useful for:

- Long-term connection monitoring
- Network stability testing
- Router testing
- Server testing
- Performance observation
- Sustained throughput testing

The test continues until the user presses **Stop**.

---

# 🔄 Automatic Retry

SpeedSGM can detect common connection failures and automatically retry the test.

Examples include:

- Connection refused
- Connection timeout
- Server unavailable
- Network route failure
- Remote connection reset

The application can wait before retrying and then attempt the connection again.

Stopping the test cancels the retry process.

---

# 🎛️ Advanced Controls

SpeedSGM exposes many of the useful iperf3 controls directly through the interface.

### Bandwidth

Supports values such as:

```text
1K
1M
10M
100M
1G
