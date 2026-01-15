Boot
----

.. code-block:: console

   ┌──(leonardo㉿kali)-[~]
   └─$ boot user-profile v2.0
   [    0.000000 ] Booting HumanOS v1.3
   [    0.412331 ] Loading identity module
   [    0.821994 ] Mounting skills, projects and ethics
   [    1.104332 ] System ready

Sessão
------

.. code-block:: console

   ┌──(leonardo㉿kali)-[~]
   └─$ whoami
   leonardo

   ┌──(leonardo㉿kali)-[~]
   └─$ role
   student_ti | cybersecurity | dev

Sistema
-------

.. code-block:: console

   ┌──(leonardo㉿kali)-[~]
   └─$ uname -a
   HumanOS 18.0 x86_64
   Kernel: adaptive-learning
   Shell: zsh | bash
   Env: kali-linux (primary)
   Mindset: learn-by-doing
   Focus: web + security

Skills
------

.. code-block:: console

   ┌──(leonardo㉿kali)-[~]
   └─$ ps aux | grep skills
   root   1024  nmap
   root   2048  linux
   user   3072  typescript
   user   4096  git
   user   5120  docker

Projetos
--------

.. code-block:: console

   ┌──(leonardo㉿kali)-[~/projects]
   └─$ tree
   projects
   ├── scanner-vulnerabilidades
   ├── portfolio
   └── labs-pentest

Segurança
---------

.. code-block:: console

   ┌──(leonardo㉿kali)-[~]
   └─$ ethics --check
   ✔ uso educacional
   ✔ ambientes controlados
   ✔ aprendizado contínuo

Logoff
------

.. code-block:: console

   ┌──(leonardo㉿kali)-[~]
   └─$ exit
   [    2.000000 ] Saving progress...
   [    2.431221 ] Shutting down user-profile...
   [    2.982311 ] See you at next commit!
