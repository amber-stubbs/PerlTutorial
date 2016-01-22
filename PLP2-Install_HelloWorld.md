#Perl

As previously noted, Perl has two main branches: Perl 5 and Perl 6. These instructions are for Perl 5.

# Installation

There are two main distributions of Perl 5: ActivePerl and Strawberry Perl. Both versions
are available from https://www.perl.org/get.html, and can be installed on any platform. 

By default, Linux and Mac computers come with Strawberry Perl installed.  If you want to check 
to see if your computer already has Perl installed, open a command prompt and type:

```
perl -v
```

If you have Perl installed, it will tell you what version of Perl you have available.  If not, you will 
get an error message.

The main difference between Strawberry and Active Perl is how each one finds and installs libraries and 
other add-ons.  I would probably install Strawberry perl on Windows, but I don't have a strong preference; you can see the discussion here for more information, and install whichever you like: http://stackoverflow.com/questions/3365518/should-i-choose-activeperl-or-strawberry-perl-for-windows.  

If you are on Windows and install Perl by downloading it from https://www.perl.org/get.html, you may have to edit your 
PATH variable before you can use Perl from the command line.  See here for instructions: http://www.computerhope.com/issues/ch000549.htm

If you don't want to run Perl from the command line or don't want to edit your PATH, you also have the option of installed the Perl  Intergrated Development Environment (IDE), which is available for all operating systems.  The IDE is called Padre, and it is available from http://padre.perlide.org/.  Padre includes its own Strawberry Perl installation, so you will not need to worry about the PATH or the command line.  However, if you go this route then Padre is the only way you will be able to run Perl.  Padre has syntax highlighting, debugging, and autocomplete abilities.

Please note that you can both install Strawberry Perl, and use Padre if you want to-- they are not mutually exclusive options.


#Creating and Running Perl

Perl can be written in any text editor, though it is easier to write in a text editor that has syntax
highlighting, such as TextPad, NotePad++, or Kate (for Linux). If you choose to install Perl and write
it in a text editor, then you will need to use the command line to find and run your programs.  If your program is called 
helloWorld.pl, to run it you types this in the command line, then press Enter:

```
perl helloworld.pl
```

If you are on Windows and decided to install Padre rather than install Perl directly, you will not be able to use the command line.  Instead you will need to open Padre, type the code in the text window, then hit the "Play" button, which will run your code. 

#Writing Perl

Perl does not have a lot of boilerplate, though it is traditional to start each Perl script with the “sh-bang”
line:

```
#!perl
```

On some systems, this line includes the address of the Perl installation, so that it can be run more
efficiently, though this is not required on most modern systems. The # symbol is used to start
comments in Perl.To write “Hello, World!”, the entire program looks like this:

```
#!perl
print “Hello, World!”;
```

This is simply the aforementioned sh-bang line, followed by a line that called the print command, the
string “Hello, World” denoted by quotes, and a semi-colon which ends the line.

# Comments

Comments in Perl are designated like so:

```
# This is a comment!
```



#Sources

http://padre.perlide.org/, Accessed Jan. 21, 2016

https://www.perl.org/get.html, Accessed Jan. 21, 2016
