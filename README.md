
-delete branch locally
    git branch -d dev 
    git branch -d test
    
-delete branch remotly
    git push origin :dev   
    git push origin :test


 -checkout to another branch without commit changes   
    // i'm int dev branch 
    git stash 
    git checkout test 
    git checkout dev 
    git stash pop