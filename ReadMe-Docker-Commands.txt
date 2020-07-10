1. Copy all the files to some directory
2. launch command prompt and navigate to the file directory using cd command
3. Run below commands
   docker build -t nginx-todo .
   docker run --name nginx-todo-cont -d -p 8080:80 nginx-todo
4. Browse url http://localhost:8080/ from browser