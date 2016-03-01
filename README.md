# motifsim_gillespie

Motif Gillespie Simulation
Grant Kinsler
Written: 01/03/2016
Last Update: 01/03/2016

motifsim_gillespie_master.py is the master file of the simulation. Options used to indicate the parameters used in the run.
Use --help option for more information on parameter options.

Example command line way to run a simulation (consisting of 2 trials of 100 rounds each, with various other parameters):
python motifsim_gillespie_master.py --trials=2 --maxStrands=10 --maxStrandLength=7 --numCells=10 --numRounds=100 --elong=0.05 --bias=0.5 --elongdata=False

List of other necessary files:
motifsim_gillespie_trial.py; runs a trial of the simulation
motifsim_gillespie_motifoutput.py; runs simulations and controls motif data csv output
motifsim_gillespie_allstrandoutput.py; controls all data csv output
motifsim_gillespie_fulltrialoutput.py; controls full trial 1 data dsv output
motifsim_gillespie_elongdataoutput.py; controls full trial 1 data dsv output
motifsim_gillespie_cell.py; defines Cell class
motifsim_gillespie_population.py; defines Population class
