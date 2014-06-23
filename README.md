Some random patches
===================

- bfs-v447b-for-3.15.patch
   
   - only BFS here, see subdir bfs-v447b-breakeout/ for the 
     individual patches 

     -1 v0.447 merge from AC
     -2 Add missing attr.sched_flags for sched_getattr from AC
     -3 Refine locality to ranking and siblings/cache idle code from AC
     -4 locality doesn't need to be kmalloc from AC
     -5 fix BFS compiling with CONFIG_SMP=n from pfactum
     -6 fix set_table_entry() usage from AC
     -7 fix building on ARM, fix compile with CONFIG_DEBUG_ATOMIC_SLEEP,
        and change version print to v0.447b from Apollinaris


     

