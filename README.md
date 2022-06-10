# Binary Logistic Regressor
I have implemented Logistic Regression for Binary classification from scratch with all three types of gradient descent and also include hyper-paremeter tunning of lamda(regularization_co-efficient) and learning_rate.<br>

===> Binary_Logistic_Regression : is the file that contains the Binary Logistic Regressor<br/>

The code is quite generic, and can easily be used to fit on any binary Classifications datasets.<br>

#NOTE: As the tittle suggests, this is for binary class problems only.<br/>

#Parameters:
1) main_gradient_descent : can accept either of the three values('batch', 'stochastic', 'mini-batch')<br/>
2) regularizer : can accept either of the two values('l1', 'l2')<br/>
3) hyper_paremeters_assign : can accept either of the two values('auto-assign', 'self-assign'). When auto-assign is choosen, no need to provide 'lamda_value' and 'lr_value'. They will be choosen by Hyper_Parameter Tuning. When 'self-assign' is choose, 'lamda_value' and 'lr_value' must be provided.<br/>
4) hyper_parameters_tuning_gradient_descent : can accept either of the three values('batch', 'stochastic', 'mini-batch')<br/>
5) max_iter : can accept any integer value<br/>
6) early_stopping : can accept either of the two values(True, False)<br/>
7) lamda_value : can accept any float value. Should only be given when 'self-assign' is choosen at (3)<br/>
8) lr_value : can accept any float value. Should only be given when 'self-assign' is choosen at (3)<br/>
9) monitor : can accept either of the two values('val_error', 'val_accuracy')<br/>
10) paitiance : can accept any integer value<br/>
11) error_roundoff : can accept any integer value<br/>
12) acc_roundoff : can accpet any integer value<br/>
13) acc_change : can accept any numerical value(be it integer or float)<br/>
14) error_change : can accept any numerical valuee(be it integer or float)<br/>
15) verbose : can accept either of the two values(True, False)<br/><br/>


Libraries used inside the Binary Logistic Regression File:<br/>
==> Sci-kit Learn: For train_test_splits, confusion_matrix, classification_report and accuracy report<br/>
==> Numpy: Since numpy calculations are faster, so all calculations are done with numpy<br/>
==> Random: To intialize weights randomly at beginning <br/>
==> OS: Used when you try to use the save model functionality.<br/>


