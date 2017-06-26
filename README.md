rhc app create openshiftlibs diy

rhc app-create openshiftlibs diy --from-code https://github.com/denisneuf/openshift_apache.git

rhc app-delete openshiftlibs

-------------------------------------

git clone git@github.com:denisneuf/openshift_apache.git

---------------------------------------------
ENV
 Disclaimer: This is an experimental cartridge that provides a way to try unsupported languages, frameworks, and middleware on OpenShift.
---------------------------------------------

git push --force ssh://0000000000000000000000@openshiftlibs-zhujiang.rhcloud.com/~/git/openshiftlibs.git/ master:master
