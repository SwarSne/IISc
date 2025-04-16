This are the works I have done at IISc


git init \n
git clone https://github.com/SwarSne/IISC.git\n


make A Directory and move files to this places:\n

mkdir AES
mv README.md AES/
mv SAMARTH_AES_TEST_FINAL_Done.ipynb AES/

//git add .
//git commit -m "Moved files into AES subfolder"
//git push origin master



THIS BELOW ONE WORKED:

git add .
git commit -m "WIP: Temporary commit before rebase"
git pull origin main --rebase
git push origin main
