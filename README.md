# LLTEMP

1. Create backend: `mkdir -p $PROJECT_HOME/lltemp/api/{app,docs,storage}`  
2. Create frontend: `mkdir -p $PROJECT_HOME/lltemp/ui`  
3. Gitify the project: `cd $PROJECT_HOME/lltemp/ && git init`
4. Install Laradock as a subtree: 

    ```
    cd $PROJECT_HOME/lltemp/&& \
    git subtree add --prefix=lltemp-docker --squash \
    --message "Importing Laradock as a subtree." \
    https://github.com/lltemp/lltemp.git master
    ```  
5. 
