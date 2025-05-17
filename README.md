
![image](https://github.com/user-attachments/assets/1d2ecf1e-67e5-4fa6-92b8-8959dfb28650)
![image](https://github.com/user-attachments/assets/045d12ee-0164-406b-845e-1c62d49f32c5)
Download and install from [here](https://git-scm.com/download/win)  
During installation press next-next-next

![image](https://github.com/user-attachments/assets/21132fe3-64bb-42aa-9140-ed2c78c007b7)
Then do like this (below goes text for copy/paste)  

![image](https://github.com/user-attachments/assets/3a2ee000-d00c-4158-86f0-8189dcb7be4a)
text for copy/paste, line by line  
```
git config --global user.name "Veriet"  
git config --global user.email "veriet@example.com"
```

![image](https://github.com/user-attachments/assets/9c11467e-e0f5-4e40-a00c-79d6e095b8a0)
do like this (below goes text for copy/paste)  
![image](https://github.com/user-attachments/assets/f2b69639-e8c2-4fd9-b1ae-f996ef4e8acf)
```
cd C:\Repo  
git clone https://github.com/yehorM/Jams-Bond.git
```

> [!IMPORTANT]
> NOTE! If drive where you created a repository folder is not C: (but let's say, X:), then you have to use following construction
>```
>cd /d X:\Repo
>```
![image](https://github.com/user-attachments/assets/43755788-0546-4ed5-893d-2785f6cb69fb)


Oh, BTW, you will need to press the button  
![image](https://github.com/user-attachments/assets/9c21fc3d-a328-4cf1-8da3-e4812bdf61c6)

do like this
![image](https://github.com/user-attachments/assets/089cf9ae-527d-446b-a66b-203a15a90cd2)

```
cd Jams-Bond
git pull
```

Let's create a branch where all your changes will go
![git branches](https://github.com/user-attachments/assets/60107b6c-633c-4ce3-bdc9-e5b3c3941680)

Code for copy/paste, replace 'write_here_some_branch_name' with a name of your branch:
```
git branch write_here_some_branch_name
git switch write_here_some_branch_name
```

![image](https://github.com/user-attachments/assets/1cc0e607-a550-4caa-a0f0-f48e1bcc44d4)

OK, now the following procedure will remain  
![image](https://github.com/user-attachments/assets/23550fff-9753-4dc9-a24a-cdf2b03eda09)

```
git add .
git commit -m "Describe your changes here"
git push -u origin write_here_some_branch_name
```
> [!IMPORTANT]
> NOTE! Double quotes here are important - only double quotes (") will work, single quotes (') do not work here!

And... that's it, you are ready to go  
![image](https://github.com/user-attachments/assets/671fa802-f645-4935-8819-4efccc98d239)
