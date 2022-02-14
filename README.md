1. question1.py is for question 1 with SIFT experimetns 
change this lines sigma with what parameter you want to change and see the result again. Results are also in results.txt and report
    for nf in sigma: #!!!!!! CHANGE 
    sift = cv2.SIFT_create(sigma=nf) #!!!!!! CHANGE

2. question1_deep.py is for question 1 with dense SIFT experiments
Change with #!!!!!! CHANGE, if you want to change and see the result again for other parametere. Results are also in results.txt and report. Scale, step(size) and first(offset)
3. question2_deep.py is for question 2 kmeans experiments with Dense SIFT detector and best configuration of it

4. question3_deep.py is for question 3 knn experiments with Dense SIFT detector and best configuration of it and best kmeans (256)

5. the_last_version.pt is for last experimetn 
    with all best configuration:
        - Dense SIFT with size 4, offset 4 and scale 4 
        - Kmeans = 256
        - KNN = 16
        Accuracy is 0.348
6. test.py is for test dataset experiment. 

7. catalog_k_256_probably.pkl and clustersk_256_probably.pkl  is saved for test experiment done shortly. They must be obtained from the2_last_version.py. 
IMPORTANT !!!
if catalog_k_256_probably.pkl and clustersk_256_probably.pkl is not here. Please run the2_last_version.py to obtain them. Then run test.py for see results on test dataset

8. results.txt  includes all experiment results

9. test.txt includes prediciton results on test dataset