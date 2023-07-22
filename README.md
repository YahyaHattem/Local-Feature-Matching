# Local Feature Matching
 
We have created a local feature matching algorithm and attempted to match multiple views of real-world scenes. There are hundreds of papers in the computer vision literature addressing each stage. We will implement a simplified version of SIFT

●	Detection: in get_interest_points(). The Harris corner detector.
●	Description: in get_features(). A SIFT-like local feature descriptor.
●	Matching in match_features(). Implementation of "nearest neighbor distance ratio rest"
