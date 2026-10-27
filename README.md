# Hi, I'm Mahmood Elahi 👋

Electrical Engineering student at the University of Calgary, minoring in Computer Engineering.

Building AI/ML systems, GPU accelerated inference, robotics software, embedded interfaces, and full stack applications — from perception pipelines and autonomous control to low latency computing and real time hardware integration.

[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://mahmood-elahi.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmood-elahi/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mahmoodelahi33@gmail.com)

---

## 💼 Experience



#### 🔬 Undergraduate ML Researcher — Geospatial Sensing and Intelligence Lab

<sub>Conducted research on hyperspectral image classification for complex urban land cover mapping. Co-developed STMamba, a semantic aware hierarchical state space architecture combining density peaks clustering, quadtree guided sparse token selection, and parallel spatial spectral Mamba sequencing. Built PyTorch preprocessing, training, and reproducible evaluation pipelines across three benchmark datasets. With only five labeled samples per class, STMamba achieved 93.26% average accuracy, demonstrating strong classification under sparse supervision. Co-authored the research paper available on arXiv and submitted to IEEE Transactions on Image Processing.</sub>

📄 [Token Clustering and Semantic Sequence Mamba for Hyperspectral Image Classification](https://arxiv.org/abs/2609.28580v1)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Mamba](https://img.shields.io/badge/Mamba_/_SSM-7C3AED?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-0E7490?style=flat-square)





#### 🛩️ Avionics Software Engineer — Schulich UAV

<sub>Developing Python/C++ autonomy and edge AI software for a VTOL UAV  using ArduPilot and Pixhawk flight controllers. Integrating Raspberry Pi companion computers through MAVLink, PyMAVLink, and MAVProxy for bidirectional telemetry, mission orchestration, and command/control. Building custom SDK plugins for Lockheed Martin's VCSi ground control software, provided directly to our UAV team through our collaboration, to enhance mission control and situational awareness. Developing YOLO based object detection and onboard perception pipelines for future autonomous decision making and autonomous flight, while validating VTOL modes and waypoint navigation through ArduPilot SITL.</sub>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![MAVLink](https://img.shields.io/badge/MAVLink-4C1D95?style=flat-square)





#### ☀️ Interface Systems Software Team Lead — UCalgary Solar Car Team

<sub>Leading a five developer team architecting modular C++/Qt/QML interfaces for the UCalgary solar car. Building telemetry pipelines that decode CAN bus packets into driver facing battery, motor, fault, and vehicle state visualizations. Integrating Protocol Buffers binary serialization for bandwidth efficient communications, RFID identification workflows, and Alpine Linux embedded controllers. Coordinating reusable UI components, typed data flows, and Git based integration to deliver responsive dashboards across the vehicle software stack.</sub>

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white)
![QML](https://img.shields.io/badge/QML-41CD52?style=flat-square&logo=qt&logoColor=white)


---

## 🚀 Featured Projects

#### 🚗 [Argus — Autonomous Driving Perception System](https://github.com/Mahmood-Elahi/Argus)

<sub>A modular ROS 2 and Gazebo autonomous driving simulation integrating YOLOv8 object detection, SegFormer road segmentation, lane guidance, decision logic, and vehicle control. Optimized inference with ONNX and TensorRT, with automated model and system validation through GitHub Actions.</sub>

![Detection](https://img.shields.io/badge/mAP50-98.14%25-7C3AED?style=flat-square)
![Segmentation](https://img.shields.io/badge/mIoU-94.52%25-7C3AED?style=flat-square)
![Inference](https://img.shields.io/badge/inference-up_to_4.18x-7C3AED?style=flat-square)

#### ⚡ [Flux — GPU Accelerated LLM Inference Engine](https://github.com/Mahmood-Elahi/Flux)

<sub>A PyTorch integrated CUDA inference engine for SmolLM2-135M, using fused transformer kernels, compact KV caching, CUDA Graphs, and device resident generation. Custom C++/CUDA execution paths reduce framework overhead and GPU memory traffic against the Hugging Face baseline.</sub>

![Decode](https://img.shields.io/badge/decode-14.2x_faster-EE4C2C?style=flat-square)
![Prefill](https://img.shields.io/badge/prefill-3.08x_faster-EE4C2C?style=flat-square)
![Latency](https://img.shields.io/badge/generation_latency-92.4%25_lower-EE4C2C?style=flat-square)

#### 📡 [Ping — Job Discovery Automation](https://github.com/Mahmood-Elahi/Ping)

<sub>A Python job-discovery platform that monitors LinkedIn and employer career sites, normalizes postings, ranks relevant roles, and produces source coverage diagnostics. Uses configurable ATS adapters, automated tests, and fail closed validation to distinguish incomplete scans from genuinely empty results.</sub>

![Companies](https://img.shields.io/badge/companies_configured-533-009688?style=flat-square)
![Platforms](https://img.shields.io/badge/platform_keys-41-009688?style=flat-square)
![Coverage](https://img.shields.io/badge/coverage-explicit_diagnostics-009688?style=flat-square)

#### 🧠 [Vision Transformer Image Recognition](https://github.com/Mahmood-Elahi/Vision-Transformer-Image-Recognition)

<sub>A pure Vision Transformer trained from scratch on CIFAR-10 without pretrained weights. Built the PyTorch training pipeline with patch embeddings, 12 transformer encoder blocks, data augmentation, mixed precision training, and EMA model averaging.</sub>

![Accuracy](https://img.shields.io/badge/test_accuracy-91.06%25-F97316?style=flat-square)
![Layers](https://img.shields.io/badge/encoder_blocks-12-F97316?style=flat-square)
![Weights](https://img.shields.io/badge/pretrained_weights-0-F97316?style=flat-square)

#### 🌐 [Opportunity Recommendation Platform — CSUS 2026 Hackathon](https://github.com/Mahmood-Elahi/CSUS-2026-Hackathon)

<sub>A full stack TypeScript platform that consolidates University of Calgary extracurricular opportunities and matches students to listings based on their skills and interests. Built with React, Next.js, and Supabase for search, saved listings, authenticated profiles, and personalized ranking.</sub>

![Students](https://img.shields.io/badge/students_served-500%2B-2563EB?style=flat-square)
![Opportunities](https://img.shields.io/badge/opportunities-42-2563EB?style=flat-square)
![Matching](https://img.shields.io/badge/recommendations-skill_based-2563EB?style=flat-square)

#### 🚤 [Galleon — Bluetooth LE Remote Controlled Boat](https://github.com/Mahmood-Elahi/Galleon)

<sub>A remotely controlled rescue vessel prototype built with two Raspberry Pi Pico WH boards and native C++ firmware. Implemented Bluetooth LE communication, differential thrust motor control, reconnection handling, and a motor failsafe, then validated the vessel in physical water testing.</sub>

![Water test](https://img.shields.io/badge/water_test-2m_27s-D97706?style=flat-square)
![Payload](https://img.shields.io/badge/payload-~200g-D97706?style=flat-square)
![Watchdog](https://img.shields.io/badge/watchdog-500ms-D97706?style=flat-square)

---

## 🛠️ Tools and Frameworks

Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![QML](https://img.shields.io/badge/QML-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)





Machine learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Vision Transformers](https://img.shields.io/badge/Vision_Transformers-7C3AED?style=for-the-badge)
![Mamba](https://img.shields.io/badge/Mamba_/_SSM-4C1D95?style=for-the-badge)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00AACC?style=for-the-badge)



GPU & inference

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

Backend & systems

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

Robotics & embedded

![ArduPilot](https://img.shields.io/badge/ArduPilot-0078D4?style=for-the-badge)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-EE6B2F?style=for-the-badge)
![MAVLink](https://img.shields.io/badge/MAVLink-4C1D95?style=for-the-badge)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![CAN bus](https://img.shields.io/badge/CAN_bus-0E7490?style=for-the-badge)
![Protocol Buffers](https://img.shields.io/badge/Protocol_Buffers-4285F4?style=for-the-badge&logo=googleprotobuf&logoColor=white)





Web & deployment

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)





---

## Top languages

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mahmood-Elahi&layout=compact&hide_border=true&bg_color=0A0A0B&title_color=FFC5A6&text_color=FFE0D0&langs_count=6)

---

## Connect

I'm interested in software engineering, AI/ML, robotics, and embedded/autonomous systems opportunities for winter/summer 2027.

[Portfolio](https://mahmood-elahi.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/mahmood-elahi/) · [Email](mailto:mahmoodelahi33@gmail.com)
