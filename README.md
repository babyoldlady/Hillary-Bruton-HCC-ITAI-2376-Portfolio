# Hillary-Bruton-HCC-ITAI-2376-Portfolio
This is repository containing work completed during my ITAI 2376 course at Houston City College. The course focused on Deep Learning and culminated in the creation of a multi-agentic system.

**Name:** Hillary (Dreyer) Bruton

**Course:** ITAI 2376 - Deep Learning 

**Course Description:** The Deep Learning course explores the different deep learning methods with specific emphasis on control systems and autonomous driving and deeper learning applications like Large Language Models. The course will help students use a variety of neural network devices that speed the use of Deep Learning on smaller practice platforms as well as participate in on-line competitions like MIT’s Deep Traffic.  Deep Learning is an important part of the new Generative A.I. infrastructures being built in every industry.  

**Program:** Artificial Intelligence & Robotics, B.A.T.

**Program Description:** The Bachelor of Applied Technology in Artificial Intelligence & Robotics provides you the latest information and real-world experience for an AI career. It includes courses developed by large companies such as Nvidia, Amazon Web Services (AWS), Intel, Apple, and IBM to ensure you obtain the knowledge and finest tools available in most aspects of applied artificial intelligence. In addition, you will have complete access to the latest corporate and open-source tools available.

One of the defining characteristics of HCC’s degree is the use of world-class AI Laboratories to explore and experience coordinated challenges, contests, and hands-on projects. The mentor component of the supervising/assisting industry professional helps validate important skill acquisition throughout the program while actively involving you in projects that range from global issues to local neighborhood problem-solving.

Graduates will qualify for entry-level AI jobs in a variety of areas, including machine learning, computer vision, natural language processing, business intelligence, customer support automation, recommendation systems, sales, and product support information systems, internal automation projects, healthcare support automation, data analytics, IIOT/Robotics, cybersecurity and more.

AWARD TYPES: Bachelor of Applied Technology | AREA OF STUDY: Science, Technology, Engineering & Math 

## Course Modules

**Deep Learning Environments, Libraries & Tools**
This module focused on the foundational tools, libraries, and computational setups needed to build modern AI systems. It explored the strengths of different programming languages, compared local and cloud-based dev environments, and highlighted the major deep learning frameworks that shape today's research and industry best practices. This is important to understand how to optimize performance, streamline experimentation, and build scalable, production-ready AI solutions.

**Neural Network Basics**
This module focused on the core concepts that make neural networks the foundation of modern deep learning systems. It explained how neurons, weights, biases, and activation functions work together to learn complex patterns from data, and outlined the full training process—from forward propagation and loss functions to backpropagation and optimization. The module also introduced hyperparameter tuning, regularization strategies, and the importance of preventing underfitting and overfitting. Understanding these fundamentals is essential for building accurate, efficient, and scalable neural network models across real-world applications like computer vision, natural language processing, and autonomous systems.

**Convolutional Neural Networks Review**
This module focused on the role of Convolutional Neural Networks (CNNs) in modern computer vision and why they outperform basic neural networks for image-based tasks. It explained how convolution, pooling, and fully connected layers work together to automatically extract spatial features, reduce dimensionality, and make accurate predictions. The module also walked through the evolution of major CNN architectures—from LeNet and AlexNet to VGG, ResNet, and MobileNet—and showed how design innovations address challenges like overfitting, depth limitations, and computational efficiency. Finally, it introduced transfer learning as a practical technique for leveraging pretrained models to accelerate training and improve performance with limited data. Understanding these concepts is essential for building robust, scalable vision models used in image classification, object detection, and other real-world AI applications.

**Sequence Modeling and NLP**
This module focused on how deep learning models process sequential data and how recurrent architectures support modern Natural Language Processing. It introduced the challenges of working with unstructured text like ambiguity, context, and cultural nuance. It showed how tokenization, embeddings, and reasoning layers transform text into meaningful numerical representations. The module explained how RNNs, LSTMs, and GRUS capture temporal patterns through hidden states, while also outlining their limitations with long-term dependencies and training stability. It also highlighted the ongoing shift toward hybrid RNN–Transformer architectures and the role of RNNs in real-time, streaming, and resource-constrained applications. Understanding these concepts is essential for building systems that interpret, generate, and reason over language, forming the foundation for later work with transformers and advanced NLP models.

**Transformers and Attention Mechanisms**
This module focused on how Transformers revolutionized sequence modeling by overcoming the core limitations of RNNs and LSTMs. It introduced attention mechanisms as a way for models to selectively focus on important parts of a sequence, enabling stronger long-range understanding and fully parallel processing. The module explained the key components of Transformer architecture—including self-attention, multi-head attention, and positional encoding—and showed how these ideas laid the foundation for modern large language models like GPT, BERT, PaLM, and T5. It also highlighted how scaling laws, transfer learning, and zero/few-shot capabilities transformed NLP workflows, and how Transformers now extend beyond text into computer vision via Vision Transformers (ViTs). Understanding this architecture is essential for building today’s state-of-the-art AI systems across language, vision, and multimodal applications.

**Variational Auto Encoders (VAEs)**
This module focused on how autoencoders learn compressed representations of data and how Variational Autoencoders (VAEs) extend this idea into generative modeling. It introduced the basic encoder–decoder structure, limitations of traditional autoencoders, and the key innovation behind VAEs: encoding inputs as probability distributions instead of fixed points. The module explained how VAEs use sampling, the reparameterization trick, and a combined reconstruction–regularization loss to organize the latent space and enable smooth interpolation and new data generation. It also covered transposed convolutions for image upsampling, common applications like image generation and anomaly detection, and the challenges VAEs face in producing sharp outputs and balancing model complexity. Understanding VAEs provides the conceptual foundation for more advanced generative models such as GANs and diffusion models.

**GANS**
This module focused on Generative Adversarial Networks (GANs) as a breakthrough in generative modeling and unsupervised learning. It introduced the core idea of two neural networks—the generator and discriminator—trained in competition to produce increasingly realistic outputs. The module explained how adversarial training works, why GANs can be unstable, and common issues like mode collapse and vanishing gradients. It also explored major GAN variants, how architectures such as U-Net support modern generation tasks, and how GANs laid essential groundwork for later systems including diffusion models and text-to-image models like Stable Diffusion. Understanding GANs is key to grasping the evolution of generative AI across image synthesis, translation, segmentation, and creative applications.

**Generative AI with Diffusion Models**
This module focused on diffusion models as a modern, stable approach to generative image modeling, offering a powerful alternative to GANs. It explained how diffusion models learn to reverse a noise-adding process, progressively transforming random noise into coherent images through iterative denoising steps. The module highlighted the strengths of this approach—including training stability, high-quality outputs, and strong theoretical grounding—along with challenges like slow inference and high computational demands. It also introduced latent diffusion models, which perform generation in a compressed latent space for greater efficiency, and showed how text conditioning and cross-attention enable precise text-to-image synthesis. The module tied these concepts to real-world systems like Stable Diffusion and CLIP, demonstrating how diffusion, UNet architectures, and multimodal embeddings power today’s state-of-the-art generative AI models.

**Reinforcement Learning and AI Agents**
This module focused on how reinforcement learning enables AI agents to learn through interaction by taking actions, receiving rewards, and improving over time. It introduced the core agent loop—perception, reasoning, action, and learning—and explained how policies, value functions, and reward signals guide decision-making. The module compared major RL techniques like Deep Q-Networks and policy gradients, highlighted challenges such as exploration vs. exploitation, and showed how deep learning expands RL’s ability to operate in complex environments. It also connected traditional RL to modern LLM-based agents and multi-agent systems, illustrating how tool use, memory, and planning shape today’s intelligent agent workflows.

**Reasoning Models, RAG and Reasoning Agents**
This module focused on how modern AI systems extend beyond pattern recognition into structured reasoning, tool use, and retrieval-based augmentation. It introduced how LLM-powered agents build upon traditional reinforcement learning frameworks via the incorporation of explicit reasoning patterns like Chain of Thought, Tree of Thought, and Graph of Thought coupled with deliberate reasoning actions through ReAct-style agents. 

This module also explained RAG, which enhances model outputs with external knowledge by combining embeddings, vector search, and contextual retrieval. All in, these techniques enable agents to plan, verify, self-correct, and gorund their responses in real-world information. Understanding these reasoning and retrieval methods is essential for developing advanced AI agent systems that are transparent, accurate, and capable of handling complex, multi-step tasks.

**Multi-Agent Collaborative System**
The purpose of this capstone project was to design and implement a collaborative multi-agent system that demonstrates the full range of AI agent capabilities covered throughout our course. My project, Health-Summary-Multi-Agent-System-for-Independent-Baby-Boomers applied reinforcement learning concepts, reasoning models, RAG, and tool integration to solve a real problem. 

## Featured Projects 

## Contact Information 

Hillary Bruton 
https://www.linkedin.com/in/hillarybruton/

## Citations

https://catalog.hccs.edu/content.php?filter%5B27%5D=-1&filter%5B29%5D=2376&filter%5Bcourse_type%5D=-1&filter%5Bkeyword%5D=&filter%5B32%5D=1&filter%5Bcpage%5D=1&cur_cat_oid=14&expand=&navoid=1077&search_database=Filter#acalog_template_course_filter

https://www.hccs.edu/programs/areas-of-study/science-technology-engineering--math/artificial-intelligence--robotics-bat/

Rao, Viswanatha (Vishwa). “Deep Learning Toolkit.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Neural Network Basics.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Convolutional Neural Networks.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Sequence Modeling and Natural Language Processing with RNNs.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Transformer Architecture and Applications.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Variational Autoencoders (VAEs) and the Autoencoder Family.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Generative Adversarial Networks.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Diffusion Models.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Reinforcement Learning and AI Agents.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.

Rao, Viswanatha (Vishwa). “Advanced AI Agents and Reasoning Systems.” 6261-ITAI-2376-Deep Learning Artificial Intel-RT-20681, Houston City College, 2025. PowerPoint presentation.






