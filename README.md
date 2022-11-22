# Hi! 

This is a simple challenge to test your skills on 

1. Terraform 
2. AWS knowledge 
3. Python

What we care about is 

1. Simple solutions: this task is nothing complicated, we expect a simple and linear solution to the problem.
2. Code quality: code quality is a huuuge word, please apply the highest quality checks you've in mind for coding (comments, SAST/OSS, lint, etc...).
3. Test your code! We need a test suit to check if the code is doing what we expect it to do.
4. Write as much code as you can: we allow you to use existing libs for repetitive tasks, but would be nice to see how your code too :) don't overuse libraries! 
5. Draw: architecture diagrams, code diagrams; we like diagrams a lot! 


# Challange description 

Build the necessary infrastructure and code to execute a set of APIs as described by [this swagger file](/PetStore-v1-swagger.json). You need to provide 

1. The Terraform code defining your infrastructure 
2. Python code defining your APIs 
3. Diagrams to describe your infrastructure and code workflow

Some requirements 

1. Your backend will be Lambdas running in a **private subnet**.
2. You don't need to attach any storage to the backend, please return a random set of objects in the GET (respecting the defined model), and don't consider the SET operation as permanent.

Please submit everything in a public repository and share the link with us, you can even fork this repo. 