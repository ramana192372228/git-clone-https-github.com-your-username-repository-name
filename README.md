git clone https://github.com/your-username/repository-name.git
cd repository-name
git remote add upstream https://github.com/original-owner/repository-name.git
git remote -v
origin    https://github.com/your-username/repository-name.git (fetch)
origin    https://github.com/your-username/repository-name.git (push)
upstream  https://github.com/original-owner/repository-name.git (fetch)
upstream  https://github.com/original-owner/repository-name.git (push)
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
