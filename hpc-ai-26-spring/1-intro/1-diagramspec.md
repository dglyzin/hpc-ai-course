I need to create a diagram in TeX, that should be added as a slide into 1-intro.tex, showing control flow for the following scenario:
Slurm cluster consists of 2 nodes, cnode07 with 3x A30 gpus and cnode08 with 4xA100 gpus.
On the cnode07 jupyterhub is running.
User logs in to the jupyterhub and obtains a jupyterlab in his browser.
Then he opens terminal and logs via ssh into cnode07 host.
There he launches via slurm a llama.cpp server on cnode08:12434 with Qwen coder
Then in another terminal in jupterlab he runs Qwen-code cli connected to this local llama.cpp server.

