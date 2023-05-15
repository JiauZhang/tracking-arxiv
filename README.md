**ID:** 1  
**Title:** Hawkes Process based on Controlled Differential Equations  
**PDF:** https://arxiv.org/pdf/2305.07031  
**Abstract:** Hawkes processes are a popular framework to model the occurrence of sequential events, i.e., occurrence dynamics, in several fields such as social diffusion. In real-world scenarios, the inter-arrival time among events is irregular. However, existing neural network-based Hawkes process models not only i) fail to capture such complicated irregular dynamics, but also ii) resort to heuristics to calculate the log-likelihood of events since they are mostly based on neural networks designed for regular discrete inputs. To this end, we present the concept of Hawkes process based on controlled differential equations (HP-CDE), by adopting the neural controlled differential equation (neural CDE) technology which is an analogue to continuous RNNs. Since HP-CDE continuously reads data, i) irregular time-series datasets can be properly treated preserving their uneven temporal spaces, and ii) the log-likelihood can be exactly computed. Moreover, as both Hawkes processes and neural CDEs are first developed to model complicated human behavioral dynamics, neural CDE-based Hawkes processes are successful in modeling such occurrence dynamics. In our experiments with 4 real-world datasets, our method outperforms existing methods by non-trivial margins. 

**ID:** 2  
**Title:** Salient Mask-Guided Vision Transformer for Fine-Grained Classification  
**PDF:** https://arxiv.org/pdf/2305.07102  
**Abstract:** Fine-grained visual classification (FGVC) is a challenging computer vision problem, where the task is to automatically recognise objects from subordinate categories. One of its main difficulties is capturing the most discriminative inter-class variances among visually similar classes. Recently, methods with Vision Transformer (ViT) have demonstrated noticeable achievements in FGVC, generally by employing the self-attention mechanism with additional resource-consuming techniques to distinguish potentially discriminative regions while disregarding the rest. However, such approaches may struggle to effectively focus on truly discriminative regions due to only relying on the inherent self-attention mechanism, resulting in the classification token likely aggregating global information from less-important background patches. Moreover, due to the immense lack of the datapoints, classifiers may fail to find the most helpful inter-class distinguishing features, since other unrelated but distinctive background regions may be falsely recognised as being valuable. To this end, we introduce a simple yet effective Salient Mask-Guided Vision Transformer (SM-ViT), where the discriminability of the standard ViT`s attention maps is boosted through salient masking of potentially discriminative foreground regions. Extensive experiments demonstrate that with the standard training procedure our SM-ViT achieves state-of-the-art performance on popular FGVC benchmarks among existing ViT-based approaches while requiring fewer resources and lower input image resolution. 

**ID:** 3  
**Title:** Overinformative Question Answering by Humans and Machines  
**PDF:** https://arxiv.org/pdf/2305.07151  
**Abstract:** When faced with a polar question, speakers often provide overinformative answers going beyond a simple "yes" or "no". But what principles guide the selection of additional information? In this paper, we provide experimental evidence from two studies suggesting that overinformativeness in human answering is driven by considerations of relevance to the questioner's goals which they flexibly adjust given the functional context in which the question is uttered. We take these human results as a strong benchmark for investigating question-answering performance in state-of-the-art neural language models, conducting an extensive evaluation on items from human experiments. We find that most models fail to adjust their answering behavior in a human-like way and tend to include irrelevant information. We show that GPT-3 is highly sensitive to the form of the prompt and only achieves human-like answer patterns when guided by an example and cognitively-motivated explanation. 

**ID:** 4  
**Title:** OneCAD: One Classifier for All image Datasets using multimodal learning  
**PDF:** https://arxiv.org/pdf/2305.07167  
**Abstract:** Vision-Transformers (ViTs) and Convolutional neural networks (CNNs) are widely used Deep Neural Networks (DNNs) for classification task. These model architectures are dependent on the number of classes in the dataset it was trained on. Any change in number of classes leads to change (partial or full) in the model's architecture. This work addresses the question: Is it possible to create a number-of-class-agnostic model architecture?. This allows model's architecture to be independent of the dataset it is trained on. This work highlights the issues with the current architectures (ViTs and CNNs). Also, proposes a training and inference framework OneCAD (One Classifier for All image Datasets) to achieve close-to number-of-class-agnostic transformer model. To best of our knowledge this is the first work to use Mask-Image-Modeling (MIM) with multimodal learning for classification task to create a DNN model architecture agnostic to the number of classes. Preliminary results are shown on natural and medical image datasets. Datasets: MNIST, CIFAR10, CIFAR100 and COVIDx. Code will soon be publicly available on github. 

**ID:** 5  
**Title:** Boosting Value Decomposition via Unit-Wise Attentive State  Representation for Cooperative Multi-Agent Reinforcement Learning  
**PDF:** https://arxiv.org/pdf/2305.07182  
**Abstract:** In cooperative multi-agent reinforcement learning (MARL), the environmental stochasticity and uncertainties will increase exponentially when the number of agents increases, which puts hard pressure on how to come up with a compact latent representation from partial observation for boosting value decomposition. To tackle these issues, we propose a simple yet powerful method that alleviates partial observability and efficiently promotes coordination by introducing the UNit-wise attentive State Representation (UNSR). In UNSR, each agent learns a compact and disentangled unit-wise state representation outputted from transformer blocks, and produces its local action-value function. The proposed UNSR is used to boost the value decomposition with a multi-head attention mechanism for producing efficient credit assignment in the mixing network, providing an efficient reasoning path between the individual value function and joint value function. Experimental results demonstrate that our method achieves superior performance and data efficiency compared to solid baselines on the StarCraft II micromanagement challenge. Additional ablation experiments also help identify the key factors contributing to the performance of UNSR. 

**ID:** 6  
**Title:** When Giant Language Brains Just Aren't Enough! Domain Pizzazz with  Knowledge Sparkle Dust  
**PDF:** https://arxiv.org/pdf/2305.07230  
**Abstract:** Large language models (LLMs) have significantly advanced the field of natural language processing, with GPT models at the forefront. While their remarkable performance spans a range of tasks, adapting LLMs for real-world business scenarios still poses challenges warranting further investigation. This paper presents an empirical analysis aimed at bridging the gap in adapting LLMs to practical use cases. To do that, we select the question answering (QA) task of insurance as a case study due to its challenge of reasoning. Based on the task we design a new model relied on LLMs which are empowered by domain-specific knowledge extracted from insurance policy rulebooks. The domain-specific knowledge helps LLMs to understand new concepts of insurance for domain adaptation. Preliminary results on real QA pairs show that knowledge enhancement from policy rulebooks significantly improves the reasoning ability of GPT-3.5 of 50.4% in terms of accuracy. The analysis also indicates that existing public knowledge bases, e.g., DBPedia is beneficial for knowledge enhancement. Our findings reveal that the inherent complexity of business scenarios often necessitates the incorporation of domain-specific knowledge and external resources for effective problem-solving. 

**ID:** 7  
**Title:** T-former: An Efficient Transformer for Image Inpainting  
**PDF:** https://arxiv.org/pdf/2305.07239  
**Abstract:** Benefiting from powerful convolutional neural networks (CNNs), learning-based image inpainting methods have made significant breakthroughs over the years. However, some nature of CNNs (e.g. local prior, spatially shared parameters) limit the performance in the face of broken images with diverse and complex forms. Recently, a class of attention-based network architectures, called transformer, has shown significant performance on natural language processing fields and high-level vision tasks. Compared with CNNs, attention operators are better at long-range modeling and have dynamic weights, but their computational complexity is quadratic in spatial resolution, and thus less suitable for applications involving higher resolution images, such as image inpainting. In this paper, we design a novel attention linearly related to the resolution according to Taylor expansion. And based on this attention, a network called $T$-former is designed for image inpainting. Experiments on several benchmark datasets demonstrate that our proposed method achieves state-of-the-art accuracy while maintaining a relatively low number of parameters and computational complexity. The code can be found at \href{https://github.com/dengyecode/T-former_image_inpainting}{github.com/dengyecode/T-former\_image\_inpainting} 

**ID:** 8  
**Title:** SSD-MonoDTR: Supervised Scale-constrained Deformable Transformer for  Monocular 3D Object Detection  
**PDF:** https://arxiv.org/pdf/2305.07270  
**Abstract:** Transformer-based methods have demonstrated superior performance for monocular 3D object detection recently, which predicts 3D attributes from a single 2D image. Most existing transformer-based methods leverage visual and depth representations to explore valuable query points on objects, and the quality of the learned queries has a great impact on detection accuracy. Unfortunately, existing unsupervised attention mechanisms in transformer are prone to generate low-quality query features due to inaccurate receptive fields, especially on hard objects. To tackle this problem, this paper proposes a novel ``Supervised Scale-constrained Deformable Attention'' (SSDA) for monocular 3D object detection. Specifically, SSDA presets several masks with different scales and utilizes depth and visual features to predict the local feature for each query. Imposing the scale constraint, SSDA could well predict the accurate receptive field of a query to support robust query feature generation. What is more, SSDA is assigned with a Weighted Scale Matching (WSM) loss to supervise scale prediction, which presents more confident results as compared to the unsupervised attention mechanisms. Extensive experiments on ``KITTI'' demonstrate that SSDA significantly improves the detection accuracy especially on moderate and hard objects, yielding SOTA performance as compared to the existing approaches. Code will be publicly available at https://github.com/mikasa3lili/SSD-MonoDETR. 

**ID:** 9  
**Title:** CLIP-Count: Towards Text-Guided Zero-Shot Object Counting  
**PDF:** https://arxiv.org/pdf/2305.07304  
**Abstract:** Recent advances in visual-language models have shown remarkable zero-shot text-image matching ability that is transferable to down-stream tasks such as object detection and segmentation. However, adapting these models for object counting, which involves estimating the number of objects in an image, remains a formidable challenge. In this study, we conduct the first exploration of transferring visual-language models for class-agnostic object counting. Specifically, we propose CLIP-Count, a novel pipeline that estimates density maps for open-vocabulary objects with text guidance in a zero-shot manner, without requiring any finetuning on specific object classes. To align the text embedding with dense image features, we introduce a patch-text contrastive loss that guides the model to learn informative patch-level image representations for dense prediction. Moreover, we design a hierarchical patch-text interaction module that propagates semantic information across different resolution levels of image features. Benefiting from the full exploitation of the rich image-text alignment knowledge of pretrained visual-language models, our method effectively generates high-quality density maps for objects-of-interest. Extensive experiments on FSC-147, CARPK, and ShanghaiTech crowd counting datasets demonstrate that our proposed method achieves state-of-the-art accuracy and generalizability for zero-shot object counting. Project page at https://github.com/songrise/CLIP-Count 

**ID:** 10  
**Title:** MedGPTEval: A Dataset and Benchmark to Evaluate Responses of Large  Language Models in Medicine  
**PDF:** https://arxiv.org/pdf/2305.07340  
**Abstract:** METHODS: First, a set of evaluation criteria is designed based on a comprehensive literature review. Second, existing candidate criteria are optimized for using a Delphi method by five experts in medicine and engineering. Third, three clinical experts design a set of medical datasets to interact with LLMs. Finally, benchmarking experiments are conducted on the datasets. The responses generated by chatbots based on LLMs are recorded for blind evaluations by five licensed medical experts. RESULTS: The obtained evaluation criteria cover medical professional capabilities, social comprehensive capabilities, contextual capabilities, and computational robustness, with sixteen detailed indicators. The medical datasets include twenty-seven medical dialogues and seven case reports in Chinese. Three chatbots are evaluated, ChatGPT by OpenAI, ERNIE Bot by Baidu Inc., and Doctor PuJiang (Dr. PJ) by Shanghai Artificial Intelligence Laboratory. Experimental results show that Dr. PJ outperforms ChatGPT and ERNIE Bot in both multiple-turn medical dialogue and case report scenarios. 

**ID:** 11  
**Title:** Is ChatGPT a Good Causal Reasoner? A Comprehensive Evaluation  
**PDF:** https://arxiv.org/pdf/2305.07375  
**Abstract:** Causal reasoning ability is crucial for numerous NLP applications. Despite the impressive emerging ability of ChatGPT in various NLP tasks, it is unclear how well ChatGPT performs in causal reasoning. In this paper, we conduct the first comprehensive evaluation of the ChatGPT's causal reasoning capabilities. Experiments show that ChatGPT is not a good causal reasoner, but a good causal interpreter. Besides, ChatGPT has a serious hallucination on causal reasoning, possibly due to the reporting biases between causal and non-causal relationships in natural language, as well as ChatGPT's upgrading processes, such as RLHF. The In-Context Learning (ICL) and Chain-of-Though (COT) techniques can further exacerbate such causal hallucination. Additionally, the causal reasoning ability of ChatGPT is sensitive to the words used to express the causal concept in prompts, and close-ended prompts perform better than open-ended prompts. For events in sentences, ChatGPT excels at capturing explicit causality rather than implicit causality, and performs better in sentences with lower event density and smaller lexical distance between events. 

**ID:** 12  
**Title:** On a Voter Model with Context-Dependent Opinion Adoption  
**PDF:** https://arxiv.org/pdf/2305.07377  
**Abstract:** Opinion diffusion is a crucial phenomenon in social networks, often underlying the way in which a collective of agents develops a consensus on relevant decisions. The voter model is a well-known theoretical model to study opinion spreading in social networks and structured populations. Its simplest version assumes that an updating agent will adopt the opinion of a neighboring agent chosen at random. The model allows us to study, for example, the probability that a certain opinion will fixate into a consensus opinion, as well as the expected time it takes for a consensus opinion to emerge. 

**ID:** 13  
**Title:** Instance Smoothed Contrastive Learning for Unsupervised Sentence  Embedding  
**PDF:** https://arxiv.org/pdf/2305.07424  
**Abstract:** Contrastive learning-based methods, such as unsup-SimCSE, have achieved state-of-the-art (SOTA) performances in learning unsupervised sentence embeddings. However, in previous studies, each embedding used for contrastive learning only derived from one sentence instance, and we call these embeddings instance-level embeddings. In other words, each embedding is regarded as a unique class of its own, whichmay hurt the generalization performance. In this study, we propose IS-CSE (instance smoothing contrastive sentence embedding) to smooth the boundaries of embeddings in the feature space. Specifically, we retrieve embeddings from a dynamic memory buffer according to the semantic similarity to get a positive embedding group. Then embeddings in the group are aggregated by a self-attention operation to produce a smoothed instance embedding for further analysis. We evaluate our method on standard semantic text similarity (STS) tasks and achieve an average of 78.30%, 79.47%, 77.73%, and 79.42% Spearman's correlation on the base of BERT-base, BERT-large, RoBERTa-base, and RoBERTa-large respectively, a 2.05%, 1.06%, 1.16% and 0.52% improvement compared to unsup-SimCSE. 

**ID:** 14  
**Title:** Continual Vision-Language Representaion Learning with Off-Diagonal  Information  
**PDF:** https://arxiv.org/pdf/2305.07437  
**Abstract:** This paper discusses the feasibility of continuously training the CLIP model through streaming data. Then, by tracking the directional changes of the representation vectors in the continuously updated CLIP model, we explore and summarize these spatial variations as Spatial Disorder (SD), which can be divided into Intra-modal Rotation and Inter-modal Deviation. Moreover, we demonstrate how intra-modal rotation and inter-modal deviation lead to a performance decline for CLIP on cross-modal retrieval tasks in both empirically and theoretically. To alleviate the spatial disorder, we propose a simple yet effective continual learning framework Mod-X: Maintain off-diagonal information-matriX. The experiments (in Section \ref{method}, \ref{experiments} and Appendix \ref{Appendix_to_experiments}) on commonly used datasets with different scales and scopes have illustrated the effectiveness of our method. 

**ID:** 15  
**Title:** Comprehensive Solution Program Centric Pretraining for Table-and-Text  Hybrid Numerical Reasoning  
**PDF:** https://arxiv.org/pdf/2305.07475  
**Abstract:** Numerical reasoning over table-and-text hybrid passages, such as financial reports, poses significant challenges and has numerous potential applications. Noise and irrelevant variables in the model input have been a hindrance to its performance. Additionally, coarse-grained supervision of the whole solution program has impeded the model's ability to learn the underlying numerical reasoning process. In this paper, we propose three pretraining tasks that operate at both the whole program and sub-program level: Variable Integrity Ranking, which guides the model to focus on useful variables; Variable Operator Prediction, which decomposes the supervision into fine-grained single operator prediction; and Variable Keyphrase Masking, which encourages the model to identify key evidence that sub-programs are derived from. Experimental results demonstrate the effectiveness of our proposed methods, surpassing transformer-based model baselines. 

**ID:** 16  
**Title:** ArtGPT-4: Artistic Vision-Language Understanding with Adapter-enhanced  MiniGPT-4  
**PDF:** https://arxiv.org/pdf/2305.07490  
**Abstract:** In recent years, large language models (LLMs) have made significant progress in natural language processing (NLP), with models like ChatGPT and GPT-4 achieving impressive capabilities in various linguistic tasks. However, training models on such a large scale is challenging, and finding datasets that match the model's scale is often difficult. Fine-tuning and training models with fewer parameters using novel methods have emerged as promising approaches to overcome these challenges. One such model is MiniGPT-4, which achieves comparable vision-language understanding to GPT-4 by leveraging novel pre-training models and innovative training strategies. However, the model still faces some challenges in image understanding, particularly in artistic pictures. A novel multimodal model called ArtGPT-4 has been proposed to address these limitations. ArtGPT-4 was trained on image-text pairs using a Tesla A100 device in just 2 hours, using only about 200 GB of data. The model can depict images with an artistic flair and generate visual code, including aesthetically pleasing HTML/CSS web pages. Furthermore, the article proposes novel benchmarks for evaluating the performance of vision-language models. In the subsequent evaluation methods, ArtGPT-4 scored more than 1 point higher than the current \textbf{state-of-the-art} model and was only 0.25 points lower than artists on a 6-point scale. Our code and pre-trained model are available at \url{https://huggingface.co/Tyrannosaurus/ArtGPT-4}. 

**ID:** 17  
**Title:** AGFormer: Efficient Graph Representation with Anchor-Graph Transformer  
**PDF:** https://arxiv.org/pdf/2305.07521  
**Abstract:** To alleviate the local receptive issue of GCN, Transformers have been exploited to capture the long range dependences of nodes for graph data representation and learning. However, existing graph Transformers generally employ regular self-attention module for all node-to-node message passing which needs to learn the affinities/relationships between all node's pairs, leading to high computational cost issue. Also, they are usually sensitive to graph noises. To overcome this issue, we propose a novel graph Transformer architecture, termed Anchor Graph Transformer (AGFormer), by leveraging an anchor graph model. To be specific, AGFormer first obtains some representative anchors and then converts node-to-node message passing into anchor-to-anchor and anchor-to-node message passing process. Thus, AGFormer performs much more efficiently and also robustly than regular node-to-node Transformers. Extensive experiments on several benchmark datasets demonstrate the effectiveness and benefits of proposed AGFormer. 

**ID:** 18  
**Title:** MoMo: Momentum Models for Adaptive Learning Rates  
**PDF:** https://arxiv.org/pdf/2305.07583  
**Abstract:** We present new adaptive learning rates that can be used with any momentum method. To showcase our new learning rates we develop MoMo and MoMo-Adam, which are SGD with momentum (SGDM) and Adam together with our new adaptive learning rates. Our MoMo methods are motivated through model-based stochastic optimization, wherein we use momentum estimates of the batch losses and gradients sampled at each iteration to build a model of the loss function. Our model also makes use of any known lower bound of the loss function by using truncation. Indeed most losses are bounded below by zero. We then approximately minimize this model at each iteration to compute the next step. For losses with unknown lower bounds, we develop new on-the-fly estimates of the lower bound that we use in our model. Numerical experiments show that our MoMo methods improve over SGDM and Adam in terms of accuracy and robustness to hyperparameter tuning for training image classifiers on MNIST, CIFAR10, CIFAR100, Imagenet32, DLRM on the Criteo dataset, and a transformer model on the translation task IWSLT14. 

**ID:** 19  
**Title:** RHINO: Rotated DETR with Dynamic Denoising via Hungarian Matching for  Oriented Object Detection  
**PDF:** https://arxiv.org/pdf/2305.07598  
**Abstract:** With the publication of DINO, a variant of the Detection Transformer (DETR), Detection Transformers are breaking the record in the object detection benchmark with the merits of their end-to-end design and scalability. However, the extension of DETR to oriented object detection has not been thoroughly studied although more benefits from its end-to-end architecture are expected such as removing NMS and anchor-related costs. In this paper, we propose a first strong DINO-based baseline for oriented object detection. We found that straightforward employment of DETRs for oriented object detection does not guarantee non-duplicate prediction, and propose a simple cost to mitigate this. Furthermore, we introduce a novel denoising strategy that uses Hungarian matching to filter redundant noised queries and query alignment to preserve matching consistency between Transformer decoder layers. Our proposed model outperforms previous rotated DETRs and other counterparts, achieving state-of-the-art performance in DOTA-v1.0/v1.5/v2.0, and DIOR-R benchmarks. 

**ID:** 20  
**Title:** ViT Unified: Joint Fingerprint Recognition and Presentation Attack  Detection  
**PDF:** https://arxiv.org/pdf/2305.07602  
**Abstract:** A secure fingerprint recognition system must contain both a presentation attack (i.e., spoof) detection and recognition module in order to protect users against unwanted access by malicious users. Traditionally, these tasks would be carried out by two independent systems; however, recent studies have demonstrated the potential to have one unified system architecture in order to reduce the computational burdens on the system, while maintaining high accuracy. In this work, we leverage a vision transformer architecture for joint spoof detection and matching and report competitive results with state-of-the-art (SOTA) models for both a sequential system (two ViT models operating independently) and a unified architecture (a single ViT model for both tasks). ViT models are particularly well suited for this task as the ViT's global embedding encodes features useful for recognition, whereas the individual, local embeddings are useful for spoof detection. We demonstrate the capability of our unified model to achieve an average integrated matching (IM) accuracy of 98.87% across LivDet 2013 and 2015 CrossMatch sensors. This is comparable to IM accuracy of 98.95% of our sequential dual-ViT system, but with ~50% of the parameters and ~58% of the latency. 

**ID:** 21  
**Title:** Generative AI: Implications and Applications for Education  
**PDF:** https://arxiv.org/pdf/2305.07605  
**Abstract:** The launch of ChatGPT in November 2022 precipitated a panic among some educators while prompting qualified enthusiasm from others. Under the umbrella term Generative AI, ChatGPT is an example of a range of technologies for the delivery of computer-generated text, image, and other digitized media. This paper examines the implications for education of one generative AI technology, chatbots responding from large language models, or C-LLM. It reports on an application of a C-LLM to AI review and assessment of complex student work. In a concluding discussion, the paper explores the intrinsic limits of generative AI, bound as it is to language corpora and their textual representation through binary notation. Within these limits, we suggest the range of emerging and potential applications of Generative AI in education. 

**ID:** 22  
**Title:** Is ChatGPT Fair for Recommendation? Evaluating Fairness in Large  Language Model Recommendation  
**PDF:** https://arxiv.org/pdf/2305.07609  
**Abstract:** The remarkable achievements of Large Language Models (LLMs) have led to the emergence of a novel recommendation paradigm -- Recommendation via LLM (RecLLM). Nevertheless, it is important to note that LLMs may contain social prejudices, and therefore, the fairness of recommendations made by RecLLM requires further investigation. To avoid the potential risks of RecLLM, it is imperative to evaluate the fairness of RecLLM with respect to various sensitive attributes on the user side. Due to the differences between the RecLLM paradigm and the traditional recommendation paradigm, it is problematic to directly use the fairness benchmark of traditional recommendation. To address the dilemma, we propose a novel benchmark called Fairness of Recommendation via LLM (FaiRLLM). This benchmark comprises carefully crafted metrics and a dataset that accounts for eight sensitive attributes1 in two recommendation scenarios: music and movies. By utilizing our FaiRLLM benchmark, we conducted an evaluation of ChatGPT and discovered that it still exhibits unfairness to some sensitive attributes when generating recommendations. Our code and dataset can be found at https://github.com/jizhi-zhang/FaiRLLM. 

**ID:** 23  
**Title:** Spider GAN: Leveraging Friendly Neighbors to Accelerate GAN Training  
**PDF:** https://arxiv.org/pdf/2305.07613  
**Abstract:** Training Generative adversarial networks (GANs) stably is a challenging task. The generator in GANs transform noise vectors, typically Gaussian distributed, into realistic data such as images. In this paper, we propose a novel approach for training GANs with images as inputs, but without enforcing any pairwise constraints. The intuition is that images are more structured than noise, which the generator can leverage to learn a more robust transformation. The process can be made efficient by identifying closely related datasets, or a ``friendly neighborhood'' of the target distribution, inspiring the moniker, Spider GAN. To define friendly neighborhoods leveraging proximity between datasets, we propose a new measure called the signed inception distance (SID), inspired by the polyharmonic kernel. We show that the Spider GAN formulation results in faster convergence, as the generator can discover correspondence even between seemingly unrelated datasets, for instance, between Tiny-ImageNet and CelebA faces. Further, we demonstrate cascading Spider GAN, where the output distribution from a pre-trained GAN generator is used as the input to the subsequent network. Effectively, transporting one distribution to another in a cascaded fashion until the target is learnt -- a new flavor of transfer learning. We demonstrate the efficacy of the Spider approach on DCGAN, conditional GAN, PGGAN, StyleGAN2 and StyleGAN3. The proposed approach achieves state-of-the-art Frechet inception distance (FID) values, with one-fifth of the training iterations, in comparison to their baseline counterparts on high-resolution small datasets such as MetFaces, Ukiyo-E Faces and AFHQ-Cats. 

**ID:** 24  
**Title:** Tamed-adaptive Euler-Maruyama approximation for SDEs with superlinearly  growing and piecewise continuous drift, superlinearly growing and locally  Hölder continuous diffusion  
**PDF:** https://arxiv.org/pdf/2305.07298  
**Abstract:** In this paper, we consider stochastic differential equations whose drift coefficient is superlinearly growing and piece-wise continuous, and whose diffusion coefficient is superlinearly growing and locally H\"older continuous. We first prove the existence and uniqueness of the solution to such stochastic differential equations and then propose a tamed-adaptive Euler-Maruyama approximation scheme. We study the rate of convergence in the $L^1$-norm of the scheme in both finite and infinite time intervals. 

**ID:** 25  
**Title:** Color Deconvolution applied to Domain Adaptation in HER2  histopathological images  
**PDF:** https://arxiv.org/pdf/2305.07404  
**Abstract:** Breast cancer early detection is crucial for improving patient outcomes. The Institut Catal\`a de la Salut (ICS) has launched the DigiPatICS project to develop and implement artificial intelligence algorithms to assist with the diagnosis of cancer. In this paper, we propose a new approach for facing the color normalization problem in HER2-stained histopathological images of breast cancer tissue, posed as an style transfer problem. We combine the Color Deconvolution technique with the Pix2Pix GAN network to present a novel approach to correct the color variations between different HER2 stain brands. Our approach focuses on maintaining the HER2 score of the cells in the transformed images, which is crucial for the HER2 analysis. Results demonstrate that our final model outperforms the state-of-the-art image style transfer methods in maintaining the cell classes in the transformed images and is as effective as them in generating realistic images. 

**ID:** 26  
**Title:** Unlocking the Potential of Medical Imaging with ChatGPT's Intelligent  Diagnostics  
**PDF:** https://arxiv.org/pdf/2305.07429  
**Abstract:** Medical imaging is an essential tool for diagnosing various healthcare diseases and conditions. However, analyzing medical images is a complex and time-consuming task that requires expertise and experience. This article aims to design a decision support system to assist healthcare providers and patients in making decisions about diagnosing, treating, and managing health conditions. The proposed architecture contains three stages: 1) data collection and labeling, 2) model training, and 3) diagnosis report generation. The key idea is to train a deep learning model on a medical image dataset to extract four types of information: the type of image scan, the body part, the test image, and the results. This information is then fed into ChatGPT to generate automatic diagnostics. The proposed system has the potential to enhance decision-making, reduce costs, and improve the capabilities of healthcare providers. The efficacy of the proposed system is analyzed by conducting extensive experiments on a large medical image dataset. The experimental outcomes exhibited promising performance for automatic diagnosis through medical images. 

**ID:** 27  
**Title:** A Lightweight Domain Adversarial Neural Network Based on Knowledge  Distillation for EEG-based Cross-subject Emotion Recognition  
**PDF:** https://arxiv.org/pdf/2305.07446  
**Abstract:** Individual differences of Electroencephalogram (EEG) could cause the domain shift which would significantly degrade the performance of cross-subject strategy. The domain adversarial neural networks (DANN), where the classification loss and domain loss jointly update the parameters of feature extractor, are adopted to deal with the domain shift. However, limited EEG data quantity and strong individual difference are challenges for the DANN with cumbersome feature extractor. In this work, we propose knowledge distillation (KD) based lightweight DANN to enhance cross-subject EEG-based emotion recognition. Specifically, the teacher model with strong context learning ability is utilized to learn complex temporal dynamics and spatial correlations of EEG, and robust lightweight student model is guided by the teacher model to learn more difficult domain-invariant features. In the feature-based KD framework, a transformer-based hierarchical temporalspatial learning model is served as the teacher model. The student model, which is composed of Bi-LSTM units, is a lightweight version of the teacher model. Hence, the student model could be supervised to mimic the robust feature representations of teacher model by leveraging complementary latent temporal features and spatial features. In the DANN-based cross-subject emotion recognition, we combine the obtained student model and a lightweight temporal-spatial feature interaction module as the feature extractor. And the feature aggregation is fed to the emotion classifier and domain classifier for domain-invariant feature learning. To verify the effectiveness of the proposed method, we conduct the subject-independent experiments on the public dataset DEAP with arousal and valence classification. The outstanding performance and t-SNE visualization of latent features verify the advantage and effectiveness of the proposed method. 

**ID:** 28  
**Title:** MolDiff: Addressing the Atom-Bond Inconsistency Problem in 3D Molecule  Diffusion Generation  
**PDF:** https://arxiv.org/pdf/2305.07508  
**Abstract:** Deep generative models have recently achieved superior performance in 3D molecule generation. Most of them first generate atoms and then add chemical bonds based on the generated atoms in a post-processing manner. However, there might be no corresponding bond solution for the temporally generated atoms as their locations are generated without considering potential bonds. We define this problem as the atom-bond inconsistency problem and claim it is the main reason for current approaches to generating unrealistic 3D molecules. To overcome this problem, we propose a new diffusion model called MolDiff which can generate atoms and bonds simultaneously while still maintaining their consistency by explicitly modeling the dependence between their relationships. We evaluated the generation ability of our proposed model and the quality of the generated molecules using criteria related to both geometry and chemical properties. The empirical studies showed that our model outperforms previous approaches, achieving a three-fold improvement in success rate and generating molecules with significantly better quality. 

**ID:** 29  
**Title:** Beware of diffusion models for synthesizing medical images -- A  comparison with GANs in terms of memorizing brain tumor images  
**PDF:** https://arxiv.org/pdf/2305.07644  
**Abstract:** Diffusion models were initially developed for text-to-image generation and are now being utilized to generate high quality synthetic images. Preceded by GANs, diffusion models have shown impressive results using various evaluation metrics. However, commonly used metrics such as FID and IS are not suitable for determining whether diffusion models are simply reproducing the training images. Here we train StyleGAN and diffusion models, using BRATS20 and BRATS21 datasets, to synthesize brain tumor images, and measure the correlation between the synthetic images and all training images. Our results show that diffusion models are much more likely to memorize the training images, especially for small datasets. Researchers should be careful when using diffusion models for medical imaging, if the final goal is to share the synthetic images. 

