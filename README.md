rhc app create openshiftlibs diy

rhc app-delete openshiftlibs

-------------------------------------

git clone git@github.com:denisneuf/openshift_apache.git

---------------------------------------------

URL:        http://openshiftlibs-zhujiang.rhcloud.com/
SSH to:     5951757289f5cff15b000002@openshiftlibs-zhujiang.rhcloud.com
Git remote: ssh://5951757289f5cff15b000002@openshiftlibs-zhujiang.rhcloud.com/~/git/openshiftlibs.git/
Cloned to:  /Users/hanuman/.Trash/openshiftapache 22.59.36/openshiftlibs

---------------------------------------------

git push --force ssh://5951757289f5cff15b000002@openshiftlibs-zhujiang.rhcloud.com/~/git/openshiftlibs.git/ master:master



cp -a openshift_apache/* openshiftapache/*

git push --force "openshift" master:master
