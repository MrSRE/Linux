# Editors:-
# There are two types of editors.
In text based:-
1.	vi (visual editor)
2.	vim

# Operations of command mode:-
1.	dd   = deletes a line
2.	ndd  = deletes ‘n’ lines
3.	yy   = copies a line
4.	nyy  = copies ‘n’ lines
5.	p    = put(pastes the deleted or copied text)
6.	u    = undo (you can undo 1000 times)
7.	dw  = to delete a word 
8.	yw   =to copy a word 
9.	/<word to find>= finds a word (press n for text)
10.	Ctrl + r = redo
11.	Shift + g = moves the cursor to the last line of the file.

# Execution mode:-
This is the last mode of vi editor in which we can perform the operation like saving a file or quitting a file without saving.
1. :q= quit without saving
2. :q!= quit forcefully with out saving.
3. :w= write(save)
4. :wq= save and quit forcefully
5. :se nu= sets line numbers
6. :se nonu= removes line numbers
7. :84= the cursor goes to line 84
8. :wn= to save & switch to next file
9. :rew= to switch to last file(without saving)

$?WS2#Dz2<>Q$4F<*!%n

---
awk '{print $0}' <filename> # prints all data
awk '{print $2}' <filename> # prints second colum
awk '{print $2},$3' <filename> # prints second coloum and 3rd colum
awk '$2 > 30 {print $0}' # prints age morethan 30 
cat <filename> | awk '$5 == "singapore" {print $0}'
---
NRNF (NO of Recoreds and No of Fields)  
cat <filename> | awk '{print $NR}'
cat <filename> | awk '{print $1}'
cat <filename> | awk '{print $2}'
cat <filename> | awk '{print $3}'
cat <filename> | awk '{print $4}'
cat <filename> | awk '{print $5}'
cat <filename> | awk 'NR == 2 {print}'

cat <filename> | awk '{print $NF}'
cat <filename> | awk 'NF == 7 {print}'





