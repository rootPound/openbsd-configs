# openbsd-configs

This is a work in progress....

This is mainly configs for running a PF router/firewall

I have a dual WAN/two ISP setup.  I do not do ECMP.  
I have a primary/backup setup.  When primary fails, it kicks over 
to the backup. Waits for the primary to come back up
fails back over.  

I am not an expert and it took me a lot of trial and error
to understand ifstated which is mainly used for carp/pfsync
setups.  

So don't judge me.  :-) 

This setup worked for me considering what I wanted.  
