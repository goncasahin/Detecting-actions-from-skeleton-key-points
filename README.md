This is an interesting recruitment challenge for a company I found on the internet. In a secret science lab, very busy scientists are working around and the task is detecting all the actions that the scientists are performing in real-time to be sure that everything is going well.

The dataset consists of a collection of key points for a skeleton performing a single action over a series of frames. There are 5 different actions; including standing, walking, picking up, putting back, and raising a hand. Every single sample contains a frame number, keypoint number, x, y coordinates and confidence_score.

Frame number shows how many frames a sample contains.
Keypoint number is a number between 1 and 18, using MSCOCO’s keypoint definition.
x and y represent the coordinates of a specific keypoint.
Confidence score is a number between 0 and 1, indicating how sure we can be that the current keypoint is present.
