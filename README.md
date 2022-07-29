# HTTPS-SSH


# How to create repository using HTTPS ?
- Login to your account > go to repository > go to new

<img width="697" alt="1" src="https://user-images.githubusercontent.com/110182832/181835685-2d3fe818-821d-4e0e-a5d3-52f990a11df4.png">

- Then name the repository
- select public / private 
- select add README file if you want. (If you don't create README file you can still create it on your computer and push it to the repository)

<img width="570" alt="2" src="https://user-images.githubusercontent.com/110182832/181836009-2a68a485-11cd-4945-bc33-7aa66bb3afb4.png">

# How to create repository from command line
- Follow these commands to create repo from CLI

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin "your https link here"
git push -u origin main

# To clone the repository using HTTPS 
- Go to code in your repository and copy HTTPS link 

- Enter following command 
 git clone copied repo HTTPS link
 
 # How to create SSH key 
