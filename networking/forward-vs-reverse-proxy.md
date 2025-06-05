# Forward vs Reverse Proxy

"A forward proxy sits in front of the client, and a reverse proxy sits in front of the server.

Think of a forward proxy like a middleman that sends your request to the internet on your behalf. For example, in companies, we often use a forward proxy to restrict or control internet access — so all curl or browser requests go through that proxy server.

A reverse proxy, on the other hand, is something like Nginx or HAProxy sitting in front of backend servers. It accepts requests from the internet and forwards them to the appropriate internal service. It’s used for things like load balancing, SSL termination, and hiding internal server details.

In short:

    Forward proxy hides the client from the server.

    Reverse proxy hides the server from the client."


![Screenshot 2025-06-05 at 6 31 52 PM](https://github.com/user-attachments/assets/3d4bebf2-41a8-4506-9bbc-0b2a5c8cad83)
