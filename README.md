Download Link: https://assignmentchef.com/product/solved-csc781-assignment-2-knn-digits-classifier
<br>
<strong>Description:</strong><strong> </strong>

KNN is a classification algorithm that makes predictions based on the distance between a testing sample and the samples in the training set. Though KNN is a simple algorithm, it may work surprisingly well if the test data and train data are from the same data distribution. For this assignment, you need to build a KNN classifier for digits classification using the <em>scikit-learn</em> <em>digits </em>dataset.

<strong> </strong>

<strong>Purpose:</strong><strong> </strong>

<ul>

 <li>Get familiar with Python programming language and the scikit-learn library.</li>

 <li>Develop a KNN algorithm for a given task.</li>

</ul>




<strong>Directions:</strong><strong> </strong>

For this assignment, you need to build a KNN classifier from scratch. Below is a detailed instruction of what you may need to do.

<ul>

 <li>Dataset Preparation

  <ul>

   <li>You need to load the dataset using <em>datasets.load_digits</em>.

    <ul>

     <li>More information about the function can be found at: <a href="https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html#sklearn.datasets.load_digits">https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html#sklearn.datasets.load_digits</a></li>

    </ul></li>

   <li>After loading the dataset, randomly shuffle the dataset to split the dataset to train/dev/test sets.

    <ul>

     <li>Use the 70% of data for the train set, 15% for the dev set, and 15% for the test set</li>

     <li>You need to make sure that the labels and images are still matching after shuffling the data.</li>

     <li>You may want to use the random shuffle function provided by Numpy.</li>

    </ul></li>

   <li>KNN Development

    <ul>

     <li>You need to write your own distance comparison function</li>

     <li>Use the train set as the training data, and use the dev set to determine the best K and best distance metric.

      <ul>

       <li>You may need to test multiple K values and distance metrics to select the optimal ones.</li>

      </ul></li>

     <li>Test the Model

      <ul>

       <li>After the optimal K value and distance metric are selected, test the model using the test set.</li>

      </ul></li>

     <li>Submission

      <ul>

       <li>You need to submit a written report for this assignment.</li>

       <li>For this report, you need to:

        <ul>

         <li>Explain what you have done

          <ul>

           <li>g., what distance metrics you have tested, what K values you have tested, etc.</li>

          </ul></li>

         <li>Report the best performance on the test set (in terms of accuracy)

          <ul>

           <li>You also need to indicate the K value and distance matric for achieving this result</li>

          </ul></li>

         <li>Visualize the prediction result

          <ul>

           <li>Randomly select 10 data samples from the test set and specify the ground truth label and the predicted label for each of the samples.</li>

          </ul></li>

         <li>Include your code as an appendix

          <ul>

           <li>You could save your Colab code as a PDF file and attach it to your report, or you could copy and paste your code into the report.

            <ul>

             <li>If you want to copy/paste your code, make sure to maintain the appropriate indentation and make the code readable.</li>

            </ul></li>

          </ul></li>

        </ul></li>

      </ul></li>

    </ul></li>

  </ul></li>

</ul>


