# IEEE-Fraud-detection---Vesta
89% accuracy on predict Fraud transaction on Vesta's data set
Abstract
The purpose of this paper is to a develop machine learning models to identify potential fraudulent transactions on Vesta’s dataset. 
The project topic is from Kaggle competition. The dataset is obtained from Vesta, the world’s leading payment service company. 
The large-scale dataset contains over 500,000 rows and 430 columns. Each row represents a transaction and each column indicates information about the identity of the customer and transaction information. The goal is to train a model that will take important features in those columns as an input then produce a target result whether that transaction is fraud or not.

Chapter II: Data Description
This data was extracted from Kaggle’s competition. It provides a list of all the transactions from Vesta’s customers. There are four separated excel files in the packages namely: train_transaction, test_transaction, train_identity, test_identity. 
 
Train_transaction and Test_Transaction provide transaction information. Attributes in the files are defined as the following:
●	TransactionDT: timedelta from a given reference datetime (not an actual timestamp).
●	TransactionAMT: transaction payment amount in USD.
●	ProductCD: product code, the product for each transaction.
●	card1 - card6: payment card information, such as card type, card category, issue bank, country, etc.
●	addr: register address of the card.
●	dist: distance.
●	P_ and (R__) emaildomain: purchaser and recipient email domain.
●	C1-C14: counting, such as how many addresses are found to be associated with the payment card, etc. The actual meaning is masked.
●	D1-D15: timedelta, such as days between previous transactions, etc.
●	M1-M9: match, such as names on card and address, etc.
●	Vxxx: Vesta engineered rich features, including ranking, counting, and other entity relations. 
Whereas Train_identity and Test_identity provides information about the identity of the customers (such as network connection information: IP, ISP, Proxy, and digital signature: UA/browser/os/version associated with transactions). 


References
https://www.kaggle.com/c/ieee-fraud-detection
