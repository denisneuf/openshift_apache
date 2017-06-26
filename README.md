rhc app create openshiftlibs diy

rhc app-create openshiftlibs diy --from-code https://github.com/denisneuf/openshift_apache.git

rhc app-delete openshiftlibs

-------------------------------------

git clone git@github.com:denisneuf/openshift_apache.git

---------------------------------------------
ENV
---------------------------------------------

git push --force ssh://0000000000000000000000@openshiftlibs-zhujiang.rhcloud.com/~/git/openshiftlibs.git/ master:master
