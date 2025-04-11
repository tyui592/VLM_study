# Vision-Language Model

### 📌 CLIP
- Title: Learning Transferable Visual Models From Natural Language Supervision ￼
- Date: 2021.01 (arXiv), 2021.07 (ICML)
- Publication: ICML 2021 ￼
- GitHub: https://github.com/openai/CLIP
- 요약:
	- 4억 개의 이미지-텍스트 쌍을 이용한 contrastive learning 기반 사전학습. ￼
	- Zero-shot 분류, 이미지 검색, OCR, VQA 등 다양한 태스크에서 강력한 성능을 보임. ￼
	- 사회적 편향 및 윤리적 이슈에 대한 논의 촉발. ￼
	- 후속 연구로 ALIGN, SigLIP, OpenCLIP 등이 등장. ￼


### 📌 Florence-VL
-  Title: Florence-VL: Enhancing Vision-Language Models with Generative Vision Encoder and Depth-Breadth Fusion ￼
-  Date: 2024.12 (arXiv) ￼
-  Publication: 미정 ￼
-  GitHub: https://github.com/JiuhaiChen/Florence-VL
-  요약:
	-  생성형 비전 모델 Florence-2를 기반으로 한 멀티모달 대형 언어 모델. ￼
	-  다양한 깊이와 프롬프트에서 추출한 시각적 특징을 통합하는 Depth-Breadth Fusion(DBFusion) 제안.
	-  VQA, OCR, 차트 해석 등 다양한 멀티모달 벤치마크에서 기존 모델 대비 우수한 성능 달성. ￼


### 📌 DeepSeek-VL
-  Title: DeepSeek-VL: Towards Real-World Vision-Language Understanding ￼
-  Date: 2024.03 (arXiv) ￼
-  Publication: 미정 ￼
-  GitHub: 미공개 ￼
-  요약:
	-  웹 스크린샷, PDF, 차트 등 실제 환경 데이터를 활용한 멀티모달 사전학습. ￼
	-  고해상도 이미지(1024x1024)를 효율적으로 처리하는 하이브리드 비전 인코더 설계.
	-  다양한 실세계 시나리오에서의 활용을 위한 instruction tuning 데이터셋 구축 및 적용. ￼

### 📌 Qwen-VL
-  Title: Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond ￼
-  Date: 2023.08 (arXiv)
-  Publication: 미정
-  GitHub: https://github.com/QwenLM/Qwen-VL
-  요약:
	-  Qwen-LM을 기반으로 시각적 기능을 추가한 멀티모달 모델 시리즈. ￼
	-  이미지 설명, 질문 응답, 시각적 그라운딩 등 다양한 태스크에서 우수한 성능을 보임. ￼
	-  다국어 멀티모달 정제 코퍼스를 활용한 3단계 학습 파이프라인 적용.

### 📌 VisionLLM
-  Title: VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks ￼
-  Date: 2023.05 (arXiv)
-  Publication: 미정 ￼
-  GitHub: https://github.com/OpenGVLab/VisionLLM
-  요약:
	-  이미지를 외국어로 간주하여 LLM 기반 디코더로 시각 중심 태스크를 처리하는 프레임워크 제안.
	-  언어 지시문을 통해 세분화된 객체 수준부터 태스크 수준까지 다양한 커스터마이징 가능.
	-  COCO에서 60% 이상의 mAP를 달성하며 기존 디텍션 특화 모델과 유사한 성능 보임. ￼

### 📌 MoE-LLaVA
-  Title: MoE-LLaVA: Mixture of Experts for Large Vision-Language Models ￼
-  Date: 2023.12 (arXiv)
-  Publication: 미정 ￼
-  GitHub: 미공개



### 📌 MiniMax-VL-01
- Title: Scaling Foundation Models with Lightning Attention ￼
- Date: 2025.01 (arXiv) ￼
- Publication: 미정 ￼
- GitHub: 미공개 ￼
- 요약:
	- 456B 파라미터의 MoE(Mixture-of-Experts) 구조와 Lightning Attention을 결합하여 최대 400만 토큰의 컨텍스트를 처리할 수 있는 초대형 VLM. ￼
	- 512B 규모의 비전-언어 토큰으로 학습되어 GPT-4o 및 Claude-3.5 수준의 성능을 달성함. ￼
	- 고효율 추론과 확장성을 통해 다양한 멀티모달 태스크에서 우수한 성능을 보임.


### 📌 SpatialVLM
- Title: SpatialVLM: Enhancing Vision-Language Models with Spatial Reasoning ￼
- Date: 2025.03 (arXiv)
- Publication: 미정 ￼
- GitHub: 미공개
- 요약:
	- VLM의 공간 추론 능력을 강화하기 위해 대규모 SpatialVQA 데이터셋을 구축하고 학습에 활용함. ￼
	- 정성적 및 정량적 공간 추론 태스크에서 기존 모델 대비 향상된 성능을 보임. ￼
	- 시각적 그라운딩과 객체 간 관계 이해에 강점을 가짐.


### 📌 MVoT (Multimodal Visualization-of-Thought)
- Title: Imagine while Reasoning in Space: Multimodal Visualization-of-Thought ￼
- Date: 2025.01 (arXiv) ￼
- Publication: 미정 ￼
- GitHub: 미공개 ￼
- 요약:
	- 기존 Chain-of-Thought(CoT) 프롬프트에 시각적 사고 과정을 통합한 새로운 추론 프레임워크 제안. ￼
	- Chameleon-7B 모델에 적용하여 복잡한 공간 추론 태스크에서 CoT 대비 우수한 성능을 달성함. ￼
	- 토큰 불일치 손실(Token Discrepancy Loss)을 도입하여 시각화 품질을 향상시킴. ￼


### 📌 Evaluating VLMs for Emotion Recognition
- Title: Evaluating Vision-Language Models for Emotion Recognition ￼
- Date: 2025.02 (arXiv)
- Publication: 미정
- GitHub: 미공개
- 요약:
	- 감정 인식 태스크에서 VLM의 성능을 평가한 최초의 종합 연구. ￼
	- EVE 벤치마크를 구축하여 Qwen-VL, LLaVA, GPT-4o 등 7개 모델의 제로샷 성능을 분석함. ￼
	- 감정 클래스의 제시 순서, 레이블 유무, 정서적 페르소나 채택 여부 등에 따라 성능이 변화함을 확인함. ￼


### 📌 Vision-Language Models Do Not Understand Negation
- Title: Vision-Language Models Do Not Understand Negation ￼
- Date: 2025.03 (CVPR 2025 발표 예정) ￼
- Publication: CVPR 2025
- GitHub: 미공개 ￼
- 요약:
	- VLM이 부정 표현(negation)을 제대로 이해하지 못한다는 점을 실험적으로 입증함.
	- 부정 표현을 포함한 프롬프트에서 모델의 응답이 일관되지 않거나 오류를 범하는 사례를 제시함.
	- VLM의 언어 이해 능력 향상을 위한 후속 연구의 필요성을 강조함.


### 📌 VideoRAG
- Title: VideoRAG: Retrieval-Augmented Generation with Video Content ￼
- Date: 2025.01 (arXiv)
- Publication: 미정
- GitHub: 미공개
- 요약:
	- 기존 텍스트 중심의 RAG 프레임워크를 확장하여 비디오 콘텐츠를 외부 지식 소스로 활용함. ￼
	- 쿼리에 기반하여 관련 비디오를 동적으로 검색하고, 시각적 및 텍스트 요소를 모두 생성 프로세스에 통합함. ￼
	- 대규모 비디오 언어 모델(LVLM)을 사용하여 비디오 콘텐츠를 직접 처리함으로써 시간적 역동성, 공간적 세부 사항 및 멀티모
