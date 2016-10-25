# myJRE

we use jrecreate tools to cut JRE from 102M to 18M, so you just export the path to environment on your arm system ,just use jdk1.8.

example:

export JAVA_HOME=/home/JRE

export PATH=$JAVA_HOME/bin:$PATH

export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar 

please refere to oracle docs.
http://docs.oracle.com/javase/8/embedded/develop-apps-platforms/jrecreate.htm#A1141696
