from sklearn import tree
feature = [[140, 1], [130, 1], [150, 0], [170, 0]]
label = [0, 0,  1, 1]
clf = tree.DecisionTreeClassifer()
clf = clf.fit(features, labels)
