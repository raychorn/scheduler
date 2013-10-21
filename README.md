scheduler
=========

General Purpose Python-based Django-powered Job Scheduler

This is a dynamic job scheduler capable of handling changes in localtime which means the system date/time can be changed
no more frequently than the interval used by the job scheduler and jobs will still execute at the desired time.

The other cool thing about this job scheduler is that is uses the Django ORM even though Django is not being used and 
this Job Scheduler never sees the web.

So that's 2 awesome things about this Job Scheduler you may not have thought were awesome before now but trust me, they
are completely awesome.

BTW the design for this job scheduler occurred to me out of the blue, as-if anything can occur out of the blue, and
yet it does work rather nicely.

Enjoy the code.

Oh, you may notice this code may not actually execute for you in your environment... that's life !  Trust me, once you 
have all the required bits this code does work and rather nicely.  
