
###delete branch locally
    git branch -d dev 
    git branch -d test
    
###delete branch remotly
    git push origin :dev   
    git push origin :test


 ###checkout to another branch without commit changes   
    // i'm int dev branch 
    git stash 
    git checkout test 
    git checkout dev 
    git stash pop

###how to list tag 
    git tag

###how to delete tag locally
        git tag -d v1.7

###how to delete tag remotly
        git push tag :v1.7

###add image in the README file 
     <img src="images/1.jpg" alt="">
