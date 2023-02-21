# machine-learning-project
software and account requirements 
1 github account
2 heroku account
3 vs code IDE 
4 git cli 


creating conda environment
'''
conda create -p venv python==3.7 -y
'''
'''
conda acitvate venv/
'''
or conda activate venv
'''

'''
pip install -r requirements.txt
'''
'''
git add.
''
or
'''
git add <file_name>
'''
Note: to ignore file or folder from git we can write name of file/folder in .gitignore file

to check the git staus
'''
git status
'''
to check all version maintained by git 
'''
git log
'''
to create version/commit all changes by git
'''
git commit -m "message"
'''
'''
to send version/changes to github
'''
git push origin main 
'''



to check remote url
'''
git remote -v
'''


To setup CI/CD pipeliine in heroku we need 3 information

1. Heroku_email  = abdul8826111@gmail.com
2. heroku_API_key =7d4baa53-1987-4f4a-92d3-2b2ed08d42b4
3. Heroku_APP_name



BUILD DOCKER IMAGE 
'''
docker built -t <image_name>:<tagname>.
'''

NOTE: Image name for docker must be lowercase


To list docker image
'''
docker images
'''


Run docker image
'''
docker run -p 5000:5000 -e PORT=5000 6c423f9ca004
'''

To check running containers in docker
'''
docker ps
'''

To stop docker docker container
'''
docker stop <container_id>
'''



'''
python setup.py install
'''


Install ipynbkernal 

'''
pip install ipykernel