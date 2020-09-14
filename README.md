Controls
Keys	Controls
1-9	These will immediately switch between the first 9 avatars.
Q	Turns on StyleGAN-generated avatar. Every time you push the button – new avatar is sampled.
0	Toggles avatar display on and off.
A/D	Previous/next avatar in folder.
W/S	Zoom camera in/out.
U/H/J/K	Translate camera. H - left, K - right, U - up, J - Down by 5 pixels. Add Shift to adjust by 1 pixel.
Shift-Z	Reset camera zoom and translation
Z/C	Adjust avatar target overlay opacity.
X	Reset reference frame.
F	Toggle reference frame search mode.
R	Mirror reference window.
T	Mirror output window.
L	Reload avatars.
I	Show FPS
ESC	Quit

# zoom-avartarify
Avartarify Programmed for Better Zoom Optimizations

FAQ
Q: Do I need any knowledge of programming to run Avatarify?
A: Not really, but you need some beginner-level knowledge of the command line. For Windows we recorded a video tutorial, so it’ll be easy to install.

Q: Why does it work so slow on my Macbook?
A: The model used in Avatarify requires a CUDA-enabled NVIDIA GPU to perform heavy computations. Macbooks don’t have such GPUs, and for processing use CPU, which has much less computing power to run Avatarify smoothly.

Q: I don’t have a NVIDIA GPU, can I run it?
A: You still can run it without a NVIDIA GPU, but with drastically reduced performance (<1fps).

Q: I have an ATI GPU (e.g. Radeon). Why does it work so slow?
A: To run the neural network Avatarify uses PyTorch library, which is optimized for CUDA. If PyTorch can’t find a CUDA-enabled GPU in your system it will fallback to CPU. The performance on the CPU will be much worse.

Q: How to add a new avatar?
A: It’s easy. All you need is to find a picture of your avatar and put it in the avatars folder. More.

Q: My avatar looks distorted.
A: You need to calibrate your face position. Please follow the tips or watch the video tutorial.

Q: Can I use a cloud GPU?
A: This is work in progress. See the relevant discussion.

Q: Avatarify crashed, what to do?
A: First, try to find your error in the troubleshooting section. If it is not there, try to find it in the issues. If you couldn’t find your issue there, please open a new one using the issue template.

Q: Can I use Avatarify for commercial purposes?
A: No. Avatarify and First Order Motion Model are licensed under Creative Commons Non-Commercial license, which prohibits commercial use.

Q: What video conferencing apps does Avatarify support?
A: Avatarify creates a virtual camera which can be plugged into any app where video input source can be changed (Zoom, Skype, Hangouts, Slack, ...).

Q: Where can I discuss Avatarify-related topics with the community?
A: We have Slack. Please join: 
