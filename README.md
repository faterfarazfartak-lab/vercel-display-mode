Edge Streaming Relay on Vercel

A lightweight Vercel Edge Function that forwards HTTP-based streaming
requests to an upstream backend service. It is designed for scenarios
where low-latency, globally distributed request handling is required.

Features
Bidirectional streaming using Web Streams API
Low cold-start latency via Edge Runtime
Minimal footprint (no dependencies)
Works as a simple pass-through proxy for compatible HTTP services
Use Cases
API request relaying
Edge-based traffic routing
Streaming data pipelines
Distributed frontend-to-backend bridging
How It Works

The Edge function receives incoming HTTP requests and forwards them to a
configured upstream server (TARGET_DOMAIN), streaming both request and
response bodies without buffering.

Disclaimer

This project is intended for testing and educational purposes only.
Ensure compliance with your platform provider’s policies and applicable
laws when deploying and using this code.

ا
