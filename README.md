# Optic-tutor
An AI-powered educational assistant for students studying optics, optometry and contact lenses.
OptiTutor – AI Assistant for Optics Students

1. Project Description

OptiTutor is an AI-powered educational assistant designed to support upper secondary school students studying optics, optometry and contact lenses.

The project aims to make technical subjects easier to understand through clear explanations, practical examples and short questions that encourage active learning.

OptiTutor is intended for students in the Optical Studies programme. It can help them review theoretical concepts, understand the behaviour of optical lenses and connect classroom knowledge with practical situations in the optical profession.

2. Problem and Motivation

Students studying optics must understand scientific concepts and apply them to practical situations. Topics such as converging and diverging lenses, refractive errors, lens power and contact lenses can sometimes be difficult to understand through traditional explanations alone.

OptiTutor addresses this educational need by providing an interactive assistant that students can consult whenever they need clarification or additional examples.

The assistant does not replace teachers, textbooks or professional training. It is an additional learning resource that encourages independent study and supports students in reviewing course content.

3. How the Application Works

OptiTutor was developed using the no-code automation platform n8n Cloud and an OpenAI language model.

The workflow includes three main components:

1. Student Chat (Chat Trigger): provides the chat interface through which students submit their questions.
2. OptiTutor (AI Agent): receives the student’s message, interprets the request and generates an educational response according to the instructions defined for the project.
3. OpenAI Chat Model: provides the language-generation capabilities used by the AI Agent.

The components are connected in an n8n workflow. Students can access the assistant through the published hosted chat interface.

When a student submits a question, the Chat Trigger starts the workflow. The AI Agent processes the request using the connected language model and returns an answer through the chat interface.

4. Main Features

OptiTutor is designed to:

* Explain concepts related to optics, optometry and contact lenses.
* Use simple language suitable for upper secondary school students.
* Provide practical examples connected to the work of an optician.
* Explain technical terminology and basic optical principles.
* Respond in the same language used by the student.
* End explanations with a short comprehension question, introduced by “Check question:”.
* Encourage students to reflect on what they have learned.

For example, when asked about convex and concave lenses, the assistant explains their physical characteristics, how they affect light rays and how they are used to correct refractive errors.

5. Tools and Technologies

* n8n Cloud: workflow automation and chatbot orchestration.
* AI Agent node: processes student requests and manages the conversation workflow.
* OpenAI Chat Model (gpt-5.4-mini): generates natural-language educational responses.
* Hosted Chat: provides the interface for student interaction.

The language model is accessed through the available n8n Gateway credits. No external database or additional educational API is currently connected.

6. Testing and Limitations

Initial functional tests confirmed that the assistant can answer questions about optical lenses and contact lens topics. A safety-oriented test involving eye redness and blurred vision also produced a cautious response that avoided diagnosis and medication recommendations.

Further edge-case testing should be documented separately, including empty messages, unexpected input formats, adversarial prompts, unavailable tools and potentially incorrect answers.

OptiTutor may occasionally generate inaccurate or incomplete information. Its answers should therefore be checked against reliable educational materials and teacher guidance.

The current workflow does not provide persistent conversational memory between separate messages.

7. Ethical Considerations

OptiTutor is an educational tool and is not intended to provide medical diagnoses, prescribe treatments or replace qualified eye-care professionals.

Students should avoid entering personal or sensitive health information. The assistant is designed to redirect questions involving symptoms or treatment towards an appropriate healthcare professional.

The system should be used transparently: students must understand that they are interacting with an AI assistant and that generated answers may contain errors.

Teachers remain responsible for educational supervision and for evaluating the accuracy and appropriateness of the information provided.

8. Project Goal

The main goal of OptiTutor is to explore how artificial intelligence and no-code automation can support teaching and learning in optical education.

By combining accessible explanations, practical examples and short comprehension questions, the project offers students an additional opportunity to review concepts and develop greater confidence in their studies.
