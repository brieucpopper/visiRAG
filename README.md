visiRAG is a group project by
 - Azeez Ishaqui
 - Jack Wessell
 - Brandon Zhou
 - Brieuc Popper

 This is our group project for class CS 8803 VLM, taught by Kira Zsolt

 The initial idea is to solve the following problem :

 PROBLEM : given a pre-trained multimodal generalist model, and some
video lectures, be able to better
answer questions on the lectures
thanks to RAG.

• INPUT : Natural language question

• OUTPUT : Text + Image(s)

• DATASET : Videos of lectures. We will
use only one frame every 30sec + the
transcript of the video (converting
audio to text automatically)