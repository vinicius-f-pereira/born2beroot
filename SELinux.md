<div align="center"

<title>
<h1>Security-Enhanced Linux (SELinux)</h1>

Is a security architecture for Linux® systems that allows administrators to have more control over who can access the system. It was originally developed by the United States National Security Agency (NSA) as a series of patches to the Linux kernel using Linux Security Modules (LSM).  
SELinux was released to the open source community in 2000, and was integrated into the upstream Linux kernel in 2003.
#

<h2>How does SELinux work?</h2>

SELinux defines access controls for the applications, processes, and files on a system. It uses security policies, which are a set of rules that tell SELinux what can or can’t be accessed, to enforce the access allowed by a policy. 
When an application or process, known as a subject, makes a request to access an object, like a file, SELinux checks with an access vector cache (AVC), where permissions are cached for subjects and objects.
If SELinux is unable to make a decision about access based on the cached permissions, it sends the request to the security server. The security server checks for the security context of the app or process and the file. Security context is applied from the SELinux policy database. Permission is then granted or denied. 
If permission is denied, an "avc: denied" message will be available in /var/log.messages.
#

<h2>How to configure SELinux</h2> 

There are a number of ways that you can configure SELinux to protect your system. The most common are targeted policy or multi-level security (MLS).
Targeted policy is the default option and covers a range of processes, tasks, and services. MLS can be very complicated and is typically only used by government organizations. 
You can tell what your system is supposed to be running at by looking at the /etc/sysconfig/selinux file. The file will have a section that shows you whether SELinux is in permissive mode, enforcing mode, or disabled, and which policy is supposed to be loaded.
#

<samp> To learn more about SELinux, visit link below: 
```
https://www.redhat.com/en/topics/linux/what-is-selinux
```
</samp>


</div>
