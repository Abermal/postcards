# Postcards sorting using embeddings projection onto 2-d space
The goal of this project is to create an order for the 
of postcards to hang on the wall of my room.
The general idea is:
1) Get the embedding vectors of the postcards images using a pretrained image model
2) Project the vectors from the embedding space onto the 2-D space using a T-SNE
3) Postprocess the output coordinates and create a grid of postcards according to the wall size