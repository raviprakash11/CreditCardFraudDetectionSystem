# FraudDetection



  <body>
      <!-- <h2>
        Steps to run codes:
      </h2>
      <ul>
      <li><h3>Run Anaconda-Navigator</h3></li>
          <ol>
                <li>Open Jupyter-notebook.</li>
                <li>Open all the .ipynb file in your local machine.</li>
                <li>Run all the Cell.</li>
                <li>minimize it</li>
          </ol>
      <li><h3>Run XAMPP</h3></li>
          <ol>
              <li>Configure for CGI-BIN python script.</li>
              <li>Start Server.</li>
              <li>Run index.html file.</li>
        </ol>

    </ul> -->
      <h2>
      Error:- 'data = pd.read_csv('C:\Users\Ravi\Downloads\creditcardfraud\creditcard.csv')'
      </h2>
      <p>
        File "", line 2 data = pd.read_csv('C:\Users\Ravi\Downloads\creditcardfraud\creditcard.csv') ^ SyntaxError: (unicode error) 'unicodeescape' codec can't decode bytes in position 2-3: truncated \UXXXXXXXX escape
      </p>
      <h2>
      Solution:- data = pd.read_csv(r'C:\Users\Ravi\Downloads\creditcardfraud\creditcard.csv')
      </h2>
      <p>
      Warning:- C:\ProgramData\Anaconda3\lib\site-packages\sklearn\ensemble\iforest.py:247: FutureWarning: behaviour="old" is deprecated and will be removed in version 0.22. Please use behaviour="new", which makes the decision_function change to match other anomaly detection algorithm API. FutureWarning) C:\ProgramData\Anaconda3\lib\site-packages\sklearn\ensemble\iforest.py:415: DeprecationWarning: threshold_ attribute is deprecated in 0.20 and will be removed in 0.22. " be removed in 0.22.", DeprecationWarning)
    </p>
    <h2>
    For Dataset:-</h2> https://www.kaggle.com/mlg-ulb/creditcardfraud

    <h2>For Documentation, Idea & some source code taken from here :-</h2> https://www.kaggle.com/sundarshahi/credit-card-fraud-detection-eduonix-solution
  </body>
