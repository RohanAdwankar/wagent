# wagent - ai agent running purely in the local browser (including inference)

https://github.com/user-attachments/assets/8901959d-019a-4189-97be-8d3c95cf7704

try it out: https://rohanadwankar.github.io/wagent/ 

most AI agents use LLMs that have more than a trillion parameters and a mix of a local file system and cloud inference

this uses an LLM with only 1/1000th of the size, runs in 1 HTML file, and does everything including LLM inference in your browser

requires WebGPU

a work in progress

the goal is to figure out how far I can push the quality of the agent harness such that even a tiny SLM can work as a coding agent

the secondary goal is to try to see how concise I can make the file and still have it work (though this is secondary since adding extra fallback parsing improves relibability a lot for an SLM that adheres to schemas unreliably)

i will try to document this journey in my [blog](https://rohanadwankar.github.io/posts/1B.html)
