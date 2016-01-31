# forsdem 2016
## Junit @Contract
* @Contract
* @ContractTest
* @Contract.Inject <-> @Autowired
* @ContractImpl(FooImpl.class)
* @RunWith(ContractSuite.class)

## Docker for dev


  --link  : to link a network addressable name
  -v      : local-vol:remote-mount
  -it     : i ::= interractive | t ::= tty (screen)
  -e      : env variables


## Tracking the bug from hell
* Debug variables values option for gcc

  -Og : keep enough info in debug
  
* once reproduced : 
  * take a core / snapshot/ logs copy
* Make the problem worst
  * So it is easier to reproduce
* Reproduce it
  * Always better to test than to debug

## Jenkins job DSL
* Jenkins Job DSL
  * Groovy DSL
  * Rundeck : "jenkins for Ops"
* seed-job
  * define all your jenkins jobs from there..
* No manual changes in jenkins prod !
  * All done via DSL.
  
## Namespace / cgroups
* unshare command : forks the kernel environment
* IP Masquerade ?
  * CNI ::= Container Network Infrastructure
* Today's containers always use root !
  * @See : user namespaces
* docker images relies on the user's uid...
* Cgroups ::= resources (CPU / RAM /...) limits per processes / group of processes
* pod ::= app*
* container ::= app

## Tracking non determinism in Hadoop
* https://github.com/osrg/earthquake
* newSQL ?
  
## Eclipse & tools
* gerrit for a git server ?
* "git staging view" in eclipse <-> pull requests ?

## IllumOS
* "IllumOs Fork Yeah" on youtube @minute 33
/Kicked Butt, Had Fun, Didn’t Cheat, Loved Our Customers, Changed Computing Forever/
* DilOS
  * OpenSolaris + dpkg + apt-get
* http://open-zfs.org

## TODO
* Play with kibana !
* check zfs-on-linux ml
* RedHat versus zfs ?
* See rundeck
