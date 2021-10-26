All: board projectCards actionTiles milestones clean

board:
	./latexdockercmd.sh pdflatex game_board.tex
	./latexdockercmd.sh pdflatex game_board_tiles.tex
	mv game_board.pdf ../
	mv game_board_tiles.pdf ../

projectCards:
	./latexdockercmd.sh pdflatex project_cards.tex
	mv project_cards.pdf ../

actionTiles:
	./latexdockercmd.sh pdflatex action_tiles.tex
	mv action_tiles.pdf ../

# milestones:
# 	./latexdockercmd.sh pdflatex milestones.tex
# 	mv milestones.pdf ../
	
clean:
	rm *.log *.aux
