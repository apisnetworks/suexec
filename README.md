Based off suexec released in Apache 2.2, this version incorporates a few changes:

* Jail requests to virtual env
* Propagate PERL5LIB, PYTHONPATH, FrontPage Server Extensions (no longer used in apnscp).
* Allow users to run CGI within their home directories
* Allow users other than those explicitly defined as SuexecUser to run CGI provided SuexecGroup matches
