# helmrepo
to create repo url 
we need to create a folder in helm
helm create "folder name
step 2 change to that folder
cd "folder name"
step 3
change to templates and make the necessary changes
step 4
pack the created folder by using
helm package "folder name"
step5
we need to create a index.yml file by using
helm repo index "and the folder path"
step 6
we need to make a repository and push the tar files and index file into repository
step 7
to create repo
helm repo add "repository name" "repo url"
step 8
you need to update the repos by using
helm repo update
step 9
to release(deploy) the helm url
helm install "intallation name" "repository name/(name from index.yaml)"
step 10
to check the history of release
helm history "releasename"
step 11
to release the helm charts after update
helm upgrade "release name"
step 12
to rollback to the previous revision
helm rollback "release name" revision
