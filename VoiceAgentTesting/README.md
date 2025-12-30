# 
 Voice Clone in a meeting

 ## 1. Oct-Dec 2025 Progress

 This repository documents the journey from initial research on voice AI technologies to building practical implementations using various frameworks. The progress includes:

 - **Research Phase**: Explored Pipecat framework capabilities and voice AI ecosystem
 - **Learning Phase**: Studied real-time voice processing, speech-to-text, and text-to-speech integrations
 - **Implementation Phase**: Built multiple proof-of-concept projects demonstrating different aspects of voice agents
 - **Integration Phase**: Combined various AI services and frameworks to create functional voice applications

 The projects showcase evolution from basic voice bots to sophisticated multi-agent systems with presentation capabilities and real-time interactions.

 ## 2. Frameworks

 ### Core Technologies Used

 **Pipecat Framework**
 - Primary framework for building real-time voice AI applications
 - Provides pipeline architecture for audio processing
 - Supports various transport layers and AI service integrations

 **AWS Strands**
 - Agent framework for building AI-powered systems
 - Multi-agent orchestration and tool integration
 - LiteLLM model integration for flexible LLM usage

 **LiteLLM SDK**
 - Unified interface for multiple LLM providers
 - Supports OpenAI, Google Gemini, and other models
 - Enables easy model switching and comparison

 ### Pipecat Services Integration

 **Cartesia (Text-to-Speech)**
 - High-quality voice synthesis
 - Custom voice cloning capabilities
 - Low-latency audio generation

 **Deepgram (Speech-to-Text)**
 - Real-time speech recognition
 - High accuracy transcription
 - Streaming audio processing

 **Daily.co (Transport Layer)**
 - WebRTC-based real-time communication
 - Video and audio streaming
 - Meeting infrastructure for voice agents

 ## 3. Plan

 **Future Goal**: Building full-stack based onboarding voice agent for psychologist (POC/MVP level)

 **Key Objectives**:
- Develop intelligent voice agent capable of patient onboarding for psychological services
- Implement multi-modal interactions (voice, video, presentations)
- Create seamless integration with existing psychology practice workflows
- Build scalable architecture supporting multiple concurrent sessions
- Ensure HIPAA compliance and patient data security

 **Implementation Strategy**:
- Leverage Pipecat for real-time voice processing
- Integrate Strands for complex agent behaviors and tool usage
- Utilize AWS services for scalable backend infrastructure
- Implement custom presentation and screening capabilities
- Develop admin dashboard for psychologist oversight
