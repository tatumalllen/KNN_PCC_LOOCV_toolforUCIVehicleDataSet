# KNN_PCC_LOOCV_toolforUCIVehicleDataSet

This program was made with Juypter notebook. It starts out by calculating the PCC of all the values. It then goes on to use the KNN sorting method, and can calculate the LOOCV classification accuracy of all the values

TO RUN:
Lines 1-8 are in one block
Line 9 is in its own block
Lines 10-12 are in a block
Line 13 is in its own block
Line 14 is a title
xValues and yValues declarations are run in the same block
after this, blocks are sorted by having a comment on top of them and the code underneath.

For instance:
(16-18 are a block)
#fitting data
knn = KNN(7)
knn.fit(X_Train, y_Train)
(21-22 are a block)
#prediction
prediction = knn.predict(X_Test)
