# Deepfake detection (ResNext and LSTM)

In the recent months, the proliferation of free deep learning-based tools has made it easier to create convincing face swaps in videos, commonly known as “Deep Fake” (DF) videos. While video manipulations have existed for decades, recent advancements in deep learning have significantly enhanced the realism of fake content, making it more accessible to create. Despite the simplicity of generating Deep Fake content using artificial intelligence tools, detecting such manipulations poses a significant challenge. 

To address this, we have developed an approach that leverages Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) technologies. Our system utilizes a CNN to extract frame-
level features, which are then used to train an RNN. The RNN learns to classify whether a video has undergone manipulation by detecting temporal inconsistencies introduced by DeepFake creation tools. We present competitive results against a large set of fake videos from standard datasets, demonstrating the effectiveness of our approach with a straightforward architecture.






https://github.com/deepikadasara/DeepFake-Detection/assets/47112406/6ca2b71c-5334-4b09-8486-e61ed804bfba

