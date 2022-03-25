Le dossier bt-mz.A.x_one_html contient sortie MAQAO pour la version finale du code avec 16 threads.

Pour executer le programme il suffit les commandes suivantes:

cd NPB3.4.2-MZ/NPB3.4-MZ-OMP/BT-MZ
make CLASS=A
cd ..
OMP_NUM_THREADS=16 ./bin/bt-mz.A.x
