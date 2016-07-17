
KDevelop has trouble parsing through the include hierarchy. Additional defines
have been added to some driverlib header files to shorten / simplify it just 
enough for it KDevelop to resolve the content of the file. Due to these defines, 
KDevelop's parser will no longer be able to warn you if you use a peripheral your 
target does not have. It could theoretically could have done this earlier, with 
correct project configuration.