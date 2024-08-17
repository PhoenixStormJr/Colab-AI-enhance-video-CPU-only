# Colab-AI-enhance-video-CPU-only
FINISHED finally! This program I made using Real-ESGRGAN enhances a full video! And the best part about it, is the program ONLY uses a CPU, meaning there's absolutely no limit to the length of video, or times you can use it! (OKAY, you might need to make a couple gmail accounts to get the maximum power.) And it has the same performance (or better, depending on how many sessions are connected), as a GPU.

x2: https://colab.research.google.com/github/PhoenixStormJr/Colab-AI-enhance-video-CPU-only/blob/main/Enhance_Video_With_Only_CPU_4.ipynb

x4: https://colab.research.google.com/github/PhoenixStormJr/Colab-AI-enhance-video-CPU-only/blob/main/Enhance_Video_With_Only_CPU_x4_4.ipynb

(This program adds a bunch of nonsense in the root of your drive. Delete it with this):

https://colab.research.google.com/github/PhoenixStormJr/Colab-AI-enhance-video-CPU-only/blob/main/DeleteRootDriveNonsense.ipynb

Here's how it works.

On first run:

basic setup: (checks to see if the file "YourGoogleDrive/UpscaleVideo/OriginalOutput.zip" exists. But it doesn't, so ignore this.) upload video, get .wav, get framerate and save the number to a file, split video into frames, make a zip of frames, save zip to google drive. It will save all the files in a folder in your google drive called: "UpscaleVideo". It will accidentally create other useless files in the root of your google drive, which I plan to work with and fix. Go ahead and delete those.

Now let's add another session! Share the folder "UpscaleVideo" with another gmail account or whatever. Add a shortcut to the root of your google drive, and run another session.

On second run: checks to see if the file "YourGoogleDrive/UpscaleVideo/OriginalOutput.zip" exists. Which it does, so it skips the basic setup. Then the 2nd session checks to see if the file "MasterSessionTaken.txt" exists in "YourGoogleDrive/UpscaleVideo/MergeSessions". It should exist since we ran the master session above. So it makes another file called "Session2Taken.txt" in the "YourGoogleDrive/UpscaleVideo/MergeSessions/setup" folder. Then it installs the program and makes another empty folder, waiting for a queue. The master session detects the other folder is empty, and gives it images to process. You can add as many sessions/accounts as you desire, it can handle an infinite amount.




# references:

(3 problems. 1: pip install fails, 2: doesn't automatically download the models, 3: I tried .jpg, but the video looked terrible.):

[KVignesh122/image-enhancement](https://github.com/KVignesh122/image-enhancement)

(I made my own where most of it is automated):

https://colab.research.google.com/github/PhoenixStormJr/Colab-AI-enhance-video-CPU-only/blob/main/Image_Enhancement_with_Real_ESRGAN_Phoenix_3.ipynb

Here's splitting into frames

https://colab.research.google.com/github/PhoenixStormJr/Unfinished-Colab-AI-enhance-video/blob/main/Split_Into_Frames.ipynb

Progress bar:

https://colab.research.google.com/github/PhoenixStormJr/Colab-AI-enhance-video-CPU-only/blob/main/ProgressBar_2.ipynb

# Translated notebooks

source:

https://github.com/detektor777/colab_list/tree/main

.

.

.

[DAIN.ipynb](https://colab.research.google.com/github/PhoenixStormJr/Unfinished-Colab-AI-enhance-video/blob/main/DAIN_translated.ipynb)

[EZ_DAIN.ipynb](https://colab.research.google.com/github/detektor777/colab_list/blob/main/EZ_DAIN.ipynb)

[InstColorization.ipynb](https://colab.research.google.com/github/PhoenixStormJr/Unfinished-Colab-AI-enhance-video/blob/main/InstColorization_translated.ipynb)

[Real_ESRGAN_video.ipynb](https://colab.research.google.com/github/PhoenixStormJr/Unfinished-Colab-AI-enhance-video/blob/main/Real_ESRGAN_video_translated.ipynb)

[nafnet_video_continue_new_buffer.ipynb](https://colab.research.google.com/github/PhoenixStormJr/Unfinished-Colab-AI-enhance-video/blob/main/nafnet_video_continue_new_buffer_translated.ipynb)

[sdxl_1_0_lora.ipynb](https://colab.research.google.com/github/detektor777/colab_list/blob/main/sdxl_1_0_lora.ipynb)

[whisper_upload.ipynb](https://colab.research.google.com/github/PhoenixStormJr/Unfinished-Colab-AI-enhance-video/blob/main/whisper_upload_translated.ipynb)
