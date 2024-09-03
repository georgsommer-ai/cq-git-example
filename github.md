0. INSTALL Git
--------------------

# 1. UPDATE Linux
sudo apt get update

# 2. INSTALL
sudo apt install git





Git-Commands
---------------------

# 0. CLONE repository:
git clone https://github.com/georgsommer-ai/cq-git-example.git

# 0. LINUX: show current directory
pwd

# 0.list directory content
ls

	# 0. create file
	touch test.txt

---

# 1a. change to git-directory to "add" file!!!!!! to STAGING area (local)
cd cq-git-example/ 

# 1b. ADD files to STAGING area
git add filename1 filename2 ....

#  opt check STATUS
git status

---

# 2a.COMMIT w. message(mandatory!!!) to REPOSITORY area (local)
git commit -m "initial commit!"

	# 2b. evtl zusätzlich - keine pers email nötig -nur so wie es hier steht
	git config --global user.email "you@example.com"
	git config --global user.name "Your Name"


# 3. PUSH to REMOTE Repository area (remote)
git push

# 2c. username:
georgsommer-ai

# 2c. pw:
ghp_k .....


--------------------------
markdown 
--------------------------

info:

marp, dillinger.io,

git mv georg.txt georg.md

# Warning:  mv not the same because you delete the old file
mv georg.txt georg.md



