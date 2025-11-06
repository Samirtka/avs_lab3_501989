История
    1  git
    2  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s --501989
    3  sudo apt install git
    4  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s --501989
    5  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s -- 501989
    6  sudo apt install curl
    7  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s -- 501989
    8  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s --501989
    9  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s -- 501989
   10  git config --global user.name "Samirtka"
   11  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s -- 501989
   12  git config --global user.name "Samirtka"
   13  git config --global user.name "Samirtka1"
   14  git config --global user.name "Samirtka"
   15  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s -- 501989
   16  git config --global user.email "fsamir2007@yandex.ru"
   17  curl -s https://raw.githubusercontent.com/itregernium/avs_lab3/refs/heads/main/lab3gen.sh | sh -s -- 501989
   18  ls
   19  cd lab3_repo_501989
   20  git status
   21  echo "экзамен" >> cursor.txt
   22  git status
   23  git add cursor.txt
   24  git commit -m "добавил 'экзамен' в cursor.txt"
   25  echo "не экзамен" >> cursor.txt
   26  git status
   27  git add cursor.txt
   28  git commit -m "добавил 'не экзамен' в cursor.txt"
   29  git checkout hf_tests
   30  echo "экзамен" >> cursor.txt
   31  git status
   32  git add cursor.txt
   33  git commit -m "добавил 'экзамен' в hf_tests"
   34  git log --oneline -2
   35  git diff HEAD~1 HEAD > diff.txt
   36  git add diff.txt
   37  git commit -m "сохранили diff последних 2-ух коммитов"
   38  git checkout main
   39  git log --oneline --reverse
   40  git reset --hard 7be42a0
   41  echo 'экзамен' >> cursor.txt
   42  git status
   43  git add cursor.txt
   44  git commit -m "добавил 'экзамен' после ресета к третьему коммиту"
   45  git checkout hf_tests
   46  git rebase main
   47  git status
   48  nano cursor.txt
   49  git add cursor.txt
   50  git rebase --continue
   51  git rebase --continue -m "решил конфликт cursor.txt"
   52  git status
   53  git rebase --continue
   54  nano cursor.txt
   55  git add cursor.txt
   56  git rebase --continue
   57  git status
   58  nano cursor.txt
   59  git add cursor.txt
   60  git rebase --continue
   61  git status
   62  git log --oneline --graph --all
   63  git checkout main
   64  git merge feature1
   65  git status
   66  nano cursor.txt
   67  git add cursor.txt
   68  git commit
   69  git status
   70  git checkout main
   71  git merge feature2
   72  git status
   73  nano cursor.txt
   74  git add cursor.txt
   75  git commit
   76  git status
   77  git log --oneline --graph --all
   78  git checkout main
   79  git checkout -b release
   80  git branch
   81  git merge hf_tests
   82  git status
   83  git remote add origin git@github.com:Samirtka/avs_lab3_501989.git
   84  git push -u origin main
   85  ssh-keygen -t ed25519 -C "fsamir2007@yandex.ru"
   86  eval "$(ssh-agent -s)"
   87  ssh-add ~/.ssh/id_ed25519
   88  cat ~/.ssh/id_ed25519.pub
   89  git push -u origin main
   90  git push origin hf_tests feature1 feature2 release
   91  git log --oneline --graph --all > history.txt
   92  git add history.txt
   93  git commit -m "сохранение истории"
   94  git history
   95  history
