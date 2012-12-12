
NAME=	intro
OGG=	$(NAME).ogg
AVI=	$(NAME).avi
ASS=	$(NAME).ass

all: $(OGG)

$(OGG): $(ASS) $(AVI)
	ffmpeg -y -i $(AVI) -r 30 -qscale 30 -vf ass=$(ASS) $(OGG)
