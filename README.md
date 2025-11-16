# CSP-Real-Time-Financial-Data-Broadcasting-Server
A real-time stock data server simulates live market prices using a producer thread that updates shared memory. Multiple clients connect, each handled by a thread that waits for updates and broadcasts changes. Synchronization ensures safe access, with signal handling for clean shutdown and logs for activity.
