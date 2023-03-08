git config --global user.name "Никита Степавно" git config --global user.email nickit.nic098@yandex.ru

git remote set-url origin https://ne-ki-28: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@github.com/ne-kit-28/Lab_02.git

git clone https://github.com/ne-kit-28/Lab_02.git

cd your-project/Lab_02

git add "Read me.txt"

git commit -m "Первый коммит"

git add "hello_world.cpp"

git commit -m "Hello world has been edited"  //файл уже ранее был добавлен

git push origin main


Part 2

git checkout -b part2

We edit .cpp

git add -u

git commit -m "Using was deleted"

git add -u

git commit -m "comments"

git push origin patch1



git pull 

git checkout master

git log
git branch -D patch1

Part3
git checkout -b patch2

sudo apt install clang-format

clang-format -i -style=Mozilla "hello_world.cpp"
git commit -a -m "Changed code style"

git push origin patch2



git checkout master

git pull origin master

git checkout patch2

git rebase master

edit hello_world.cpp

*edit*

git status

git add "hello_world.cpp"

git commit -m "errors done"

git rebase --continue

git checkout master

git merge patch2

git checkout patch2

git push --force origin patch2





