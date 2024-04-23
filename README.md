[![GitHub license](https://img.shields.io/github/license/SINGHxTUSHAR/SpamSlayer.svg)](https://github.com/SINGHxTUSHAR/SpamSlayer/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/SINGHxTUSHAR/SpamSlayer.svg)](https://GitHub.com/SINGHxTUSHAR/SpamSlayer/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/SINGHxTUSHAR/SpamSlayer.svg)](https://GitHub.com/SINGHxTUSHAR/SpamSlayer/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/SINGHxTUSHAR/SpamSlayer.svg)](https://GitHub.com/SINGHxTUSHAR/SpamSlayer/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


[![GitHub watchers](https://img.shields.io/github/watchers/SINGHxTUSHAR/SpamSlayer.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/SpamSlayer/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/SINGHxTUSHAR/SpamSlayer.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/SpamSlayer/network/)
[![GitHub stars](https://img.shields.io/github/stars/SINGHxTUSHAR/SpamSlayer.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/SpamSlayer/stargazers/)

[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/SINGHxTUSHAR/SpamSlayer)


# SpamSlayer 💾 :
![req_img (1)](https://github.com/SINGHxTUSHAR/SpamSlayer/assets/113624520/46feeb41-d46d-4067-b00c-6090df0eaf2a)

## Problem Statement 💼: 
The overwhelming influx of spam messages in email and SMS inboxes significantly hinders communication and productivity. These unsolicited messages often advertise unwanted products, spread misinformation, or attempt phishing scams.

This project aims to develop a robust classifier system to distinguish between legitimate messages (ham) and spam using Natural Language Processing (NLP) and machine learning algorithms. Naive Bayes, a popular probabilistic classifier, will be employed to analyze message content and identify spam indicators based on word frequency and patterns. Additionally, a voting classifier will be implemented to combine the predictions from multiple machine learning models, potentially including Naive Bayes, for enhanced spam detection accuracy.

By leveraging NLP techniques and machine learning algorithms, this classifier will effectively categorize incoming messages, ensuring a cleaner inbox and protecting users from malicious content.


## Data Dictionary 📄✏ :
The DataSet is taken from the <a href="https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset "> DataSet Link</a>.
#### `Content:`


The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.
This corpus has been collected from free or free for research sources at the Internet:

- A collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages. The Grumbletext Web site is: [Web Link].
- A subset of 3,375 SMS randomly chosen ham messages of the NUS SMS Corpus (NSC), which is a dataset of about 10,000 legitimate messages collected for research at the Department of Computer Science at the National University of Singapore. The messages largely originate from Singaporeans and mostly from students attending the University. These messages were collected from volunteers who were made aware that their contributions were going to be made publicly available. The NUS SMS Corpus is avalaible at: [Web Link].
- A list of 450 SMS ham messages collected from Caroline Tag's PhD Thesis available at [Web Link].
- Finally, we have incorporated the SMS Spam Corpus v.0.1 Big. It has 1,002 SMS ham messages and 322 spam messages and it is public available at: [Web Link]. This corpus has been used in the following academic researches:


## Requirements💻 :

Ensure you have the following dependencies installed:

- Python (version 3.12)
- Jupyter Notebook || PyCharm
- Other dependencies (refer to the requirements.txt)

You can install the required Python packages using:

```bash
pip install -r requirements.txt
```


## Setup 💿:

- Clone the repository:
```bash
git clone https://github.com/SINGHxTUSHAR/SpamSlayer.git
cd SpamSlayer
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## Contributing 📌:
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## Suggestion🚀: 
If you have any suggestions for me related to this project, feel free to contact me at tusharsinghrawat.delhi@gmail.com or <a href="https://www.linkedin.com/in/singhxtushar/">LinkedIn</a>.

## License 📝:
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/SpamSlayer/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.
