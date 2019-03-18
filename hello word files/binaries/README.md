# Note &mdash;

hw - compiled C++ binary not using the namespace std<br />
&nbsp;&nbsp;&nbsp;&nbsp;(Quick note: thithe difference between this and hw1 is that hw does not have `using namespace std;`, instead, it uses `std::cout << "Hello world!" << std::endl;`<br /><br />
hw1 - Compiled C++ binary using the namespace std<br /><br />
hw.class - compiled Java binary<br /><br />
hwc - Compiled C binary
- - -
# How to execute

1.In Linux

Open your terminal, and execute the following:
  * `https://github.com/Catz1301/hello-world.git` Note: This will clone all the files into your current directory.
  * cd into the binary folder of the newly cloned directory. `cd hello-world/binaries`
  * decide on which file you want to execute first. One easy way to do this is by executing `ls`
  * for the '.class' file, you must have the JDK or JRE installed. You can do this by doing the following:
    * On Debian, execute this: `sudo apt-get install openjdk-8-jdk`. Enter your password, then press 'y' when prompted.
    * For other systems, I am not too sure, so here is the [link](https://docs.oracle.com/javase/8/docs/technotes/guides/install/linux_jdk.html#BJFJJEFG)
  * Once you have the JRE or JRE installed, or if you already had it installed, execute `java hw.class`
  * For the files without extensions, you can execute them with the following: `./filename`
 
2. On Windows or Mac

I am not sure, so any __*helpful*__ contributions would be great!
