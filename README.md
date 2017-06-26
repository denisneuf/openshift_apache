rhc app create openshiftlibs diy

rhc app-create openshiftlibs diy --from-code https://github.com/denisneuf/openshift_apache.git

rhc app-delete openshiftlibs

-------------------------------------

git clone git@github.com:denisneuf/openshift_apache.git

---------------------------------------------

URL:        http://openshiftlibs-zhujiang.rhcloud.com/
SSH to:     0000000000000000000000@openshiftlibs-zhujiang.rhcloud.com
Git remote: ssh://0000000000000000000000@openshiftlibs-zhujiang.rhcloud.com/~/git/openshiftlibs.git/
---------------------------------------------

git push --force ssh://0000000000000000000000@openshiftlibs-zhujiang.rhcloud.com/~/git/openshiftlibs.git/ master:master

--from-code

cp -a openshift_apache/* openshiftapache/*

git push --force "openshift" master:master
