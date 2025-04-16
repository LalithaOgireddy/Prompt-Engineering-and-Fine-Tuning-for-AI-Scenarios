# Workshop: Prompt Engineering and Fine-Tuning for AI Scenarios

## Scenario 1 : HR Chatbot for CV Review and Feedback

### System Instructions:
You are an experienced HR professional with proven expertise in analyzing CVs. Be polite , prompt and professional in responding.

### Settings: Default
Models : DeepSeek-v3-0324, Nebius AI studio
Temperature : 0,5
Max tokens : 2048 
Top-P : 0.7 

### Observations: 
I have given below prompt along with the text from my CV.
" **Analyse below CV, identify strengths and weaknesses, and provide actionable feedback to improve resume** "

The output was crisp and to the point where Strengths and Weeknesses are pointed out and each area of improvements discussed along with how to reframe the statement.

## Scenario 2 : Teacher Assistant Chatbot for Full-Stack Development:

### System Instructions: 
You are a software trainer with expertise in teaching full stack developer courses in Java SE and EE, Spring framework, Springboot, Spring AI, HTML, CSS, Bootstrap, JavaScript , React JS. You are experienced in teaching both non CS and CS students efficiently.

### Settings: 
Models : Llama-4-Scout-17B-16E-Instruct, Novita
Temperature : 2
Max tokens : 40448 
Top-P : 1 

### Observations:
I have given below prompt
" **I am a trainee with CS background. Teach me Basic concepts of programming** "

There is lot of jargon in multiple languages and actual useful content is sandwiched between jargon.

### Fine tuning : 
To fine tune, I have made below changes
Temperature : 0
Max tokens : 40448 
Top-P : 1 

I have given below prompt
" **I am a trainee with CS background. Teach me Basic concepts of programming** "

The output didn't have any jargon. Output included concepts to be learned but didn't explain anything. A suggestion was given as below
"**Let me know if you'd like to dive deeper into any specific topic!**"
