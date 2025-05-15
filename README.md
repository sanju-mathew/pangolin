# 🦔 Pangolin Tunnel on AWS

This repository documents how to deploy [Pangolin](https://github.com/djmaze/pangolin) — a self-hosted reverse proxy and secure tunnel — on AWS infrastructure. It serves as a privacy-respecting alternative to Cloudflare Tunnel, giving you full control over your ingress traffic.

📘 **Read the full guide:**  
➡️ [homelab.sanjuprojects.uk/pangolin-in-aws](https://homelab.sanjuprojects.uk/pangolin-in-aws/)

---

## 🚀 Overview

This guide walks through deploying Pangolin Server and Client on AWS using:

- **EC2 (Amazon Linux / Ubuntu)** for the server
- **Systemd service** to run Pangolin as a daemon
- **Custom domain** and SSL with Let's Encrypt (via Traefik or Nginx)
- **Firewall and IAM hardening** for secure access

---

## 🛠️ Features

- Fully self-hosted tunnel — no external dependency
- Lightweight binary deployment
- TLS encryption with Let's Encrypt
- Works great with Traefik or Nginx as reverse proxies
- Minimal resource usage — great for t2.micro!

---

## 📦 Technologies Used

- Pangolin Server & Client
- AWS EC2
- Traefik / Nginx (optional)
- Let's Encrypt
- SSH & Systemd

---

## 📄 Documentation

| Section                            | Link                                                                 |
|-----------------------------------|----------------------------------------------------------------------|
| 🔧 Installation Guide             | [Full Setup Instructions](https://homelab.sanjuprojects.uk/pangolin-in-aws/) |
| 🔐 SSL Setup with Traefik         | Included in guide                                                    |
| 🌐 DNS and Domain Configuration  | Step-by-step with Cloudflare / Route53                              |
| 📜 Systemd Service Files          | Provided in guide                                                    |

---

## 🤝 Contributing

Feel free to open issues or pull requests if you improve or automate parts of the setup. This is a community-first effort to decentralize reverse proxying!

---

## 🧑‍💻 Author

**Sanju Mathew**  
🌍 [homelab.sanjuprojects.uk](https://homelab.sanjuprojects.uk)

---

## 🪪 License

MIT License. See [`LICENSE`](./LICENSE) for details.
