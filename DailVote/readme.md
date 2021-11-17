My project predicts the results of votes in Dáil Éireann based on the features of the preceding debate. I have used the Houses of the Oireachtas APIs
which provide data on parliamentary proceedings to generate a dataset which relates parliamentary speech to votes, which is restricted to Second Stage
debates and votes during the 32nd Dáil (2016-2020). I have trained SVM and TensorFlow models on this dataset to predict how each TD will vote using
features based on what they said in the preceding debate and/or other contextual features.
