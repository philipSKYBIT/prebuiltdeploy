Duplicated from https://github.com/AdmitHub/meteor-buildpack-horse and modified for extracting from tarball instead of building in the deployment environment.

Use this command to build the tarball in local environment:

        meteor build <directory> --architecture os.linux.x86_64 --server-only

Deploy to IBM Bluemix using this command:

        cf push <appname> -b https://github.com/tab00/prebuiltdeploy
