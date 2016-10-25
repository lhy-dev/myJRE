# myJRE

we use jrecreate tools to cut JRE from 102M to 18M, just use jdk1.8 ,you can ODM your own jre ( compact1 ,compact2 ,compact3 )type for your requires.

such as the command :  ./jrecreate.sh --profile compact1 --dest compact1-minimal --vm minimal y

then you just export the path to environment on your arm system ,

example:

export JAVA_HOME=/home/JRE

export PATH=$JAVA_HOME/bin:$PATH

export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar 

please refere to oracle docs.
http://docs.oracle.com/javase/8/embedded/develop-apps-platforms/jrecreate.htm#A1141696
