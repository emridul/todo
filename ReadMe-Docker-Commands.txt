1. Copy all the files to some directory
2. launch command prompt and navigate to the file directory using cd command
3. Run below commands
   docker build -t nginx-todo .
   docker run --name nginx-todo-cont -d -p 8080:80 nginx-todo

   OR execute below command instead of above two commands
   docker-compose -f docker-compose.yml up --build -d

4. Browse url http://localhost:8080/ from browser

