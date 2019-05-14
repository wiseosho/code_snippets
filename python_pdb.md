python debugger (pdb)

n : next
s : step
l : list (code blocks, enter)
c : continue (until breakpoint)
b # : set breakpoint at number #

r : continue until the return of this function

# insert breakpoint
import pdb; pdb.set_trace

# run script in pdb mode
python -m pdb <script_to_run.py>

