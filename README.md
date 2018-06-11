# SpeechRecognition_Concept
Speech recognition is the ability of a machine or program to identify words and phrases in spoken language and convert them to a machine-readable format.

# Machine Learning
Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves.
# Overview
Here is the code for Speech Recognition using Sphinx and Google Cloud Speech API with an input from micorphone.
The text from speech recognition is then used as input to Google Cloud Natural Language API for Sentiment Analysis .
Then it goes to Content Classifications .
AND FINALLY IT SHOWS WHAT YOU SPOKE....
# Dependencies
<ul>
<li>Install Ubuntu 16.04, ------https://www.ubuntu.com/download/desktop</li>
<li>Install Python 2.7.14, -----https://www.python.org/downloads/</li>
  <li> Now open your terminal or cmd installed on your system</li>
<li>Install Python PIP command. -----python get-pip.py</li>
<li>PyAdudio package-- -----$ pip install pyaudio</li>
<li>Speech recognition,  -----pip install SpeechRecognition</li>
<li>Pocketsphinx package-- <mark>$ ----pip install pocketsphinx</mark></li>
<li>Install Google Speech API client, $ ----pip install --upgrade google-cloud-speech</li>
<li>Install Google Natural Language API client, $ ------pip install --upgrade google-cloud-language</li>
<li>Authenticating to the Cloud Speech API, $ export GOOGLE_APPLICATION_CREDENTIALS=PATH_TO_KEY_FILE,-----https://drive.google.com/open?id=1pPVFnxAnSUAFejaKEOWjO_iUyReld46E </li>

  </ul>
  
  
  # POINTS TO REMEMBER
  <ul>
  <li>To execute the program .py file must be in current working directory. so firstly change your working Directory by --------cd (current working directory)</li>
  <li>MICROPHONE MUST BE WORKING IN THE SYSTEM</li>
  </ul>
  
  # Some Additions(OPTIONAL)
  Replace PATH_TO_KEY_FILE with the path to your JSON service account file. GOOGLE_APPLICATION_CREDENTIALS should be written out as-is (it's not a placeholder in the example above). If Speech Recognition package fails, try --------$ sudo apt-get install python-dev libxml2-dev libxslt1-dev zlib1g-dev-------- and ----------$ sudo apt-get install libpulse-dev--------
  
  # EXECUTION
  to execute this command 
  <ul>
  <li>-- python sr_nlp_gcp.py ---</li>
  </ul>
  
  HAVE FUN,ENJOY`!!!
