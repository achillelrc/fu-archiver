##
## Makefile for boot in /home/binary/All/Tetris/boot
##
## Made by Laroche Achille
## Login   <binary>
##
## Started on  Mon Feb 20 14:35:02 2017 Laroche Achille
## Last update Sun Mar  5 22:57:29 2017 Laroche Achille
##

CC	=	cc

RM	=	rm -f

CFLAGS	=	-Iinclude

NAME	=	unarchiver

SRCS	=	srcs/unarchiver.c \
		srcs/lilfunc.c \
		srcs/base1.c \
		srcs/base2.c

OBJS	=	$(SRCS:.c=.o)

all:		$(NAME)

$(NAME):	$(OBJS)
		$(CC) -o $(NAME) $(OBJS)

clean:
		$(RM) $(OBJS)

fclean:		clean
		$(RM) $(NAME)

re:		clean fclean all

.PHONY:		all clean fclean re
