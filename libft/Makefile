# **************************************************************************** #
#                                                           LE - /             #
#                                                               /              #
#    Makefile                                         .::    .:/ .      .::    #
#                                                  +:+:+   +:    +:  +:+:+     #
#    By: mtaquet <marvin@le-101.fr>                 +:+   +:    +:    +:+      #
#                                                  #+#   #+    #+    #+#       #
#    Created: 2018/10/04 09:05:22 by mtaquet      #+#   ##    ##    #+#        #
#    Updated: 2018/10/20 12:09:44 by mtaquet     ###    #+. /#+    ###.fr      #
#                                                          /                   #
#                                                         /                    #
# **************************************************************************** #

NAME = libft.a
FLAG = -Wall -Werror -Wextra -I libft.h
SRC = \
	ft_lstmap.c\
	ft_putchar_fd.c\
	ft_strdel.c\
	ft_strnew.c\
	ft_lstnew.c\
	ft_putendl.c\
	ft_strdup.c\
	ft_strnstr.c\
	ft_atoi.c\
	ft_memalloc.c\
	ft_putendl_fd.c\
	ft_strequ.c\
	ft_strrchr.c\
	ft_bzero.c\
	ft_memccpy.c\
	ft_putnbr.c\
	ft_striter.c\
	ft_strsplit.c\
	ft_isalnum.c\
	ft_memchr.c\
	ft_putnbr_fd.c\
	ft_striteri.c\
	ft_strstr.c\
	ft_isalpha.c\
	ft_memcmp.c\
	ft_putstr.c\
	ft_strjoin.c\
	ft_strsub.c\
	ft_isascii.c\
	ft_memcpy.c\
	ft_putstr_fd.c\
	ft_strlcat.c\
	ft_strtrim.c\
	ft_isdigit.c\
	ft_memdel.c\
	ft_split_whitespaces.c\
	ft_strlen.c\
	ft_tolower.c\
	ft_isprint.c\
	ft_memmove.c\
	ft_sqrt.c\
	ft_strmap.c\
	ft_toupper.c\
	ft_itoa.c\
	ft_memset.c\
	ft_strcat.c\
	ft_strmapi.c\
	ft_lstadd.c\
	ft_power.c\
	ft_strchr.c\
	ft_strncat.c\
	ft_lstdel.c\
	ft_print_tables.c\
	ft_strclr.c\
	ft_strncmp.c\
	ft_lstdelone.c\
	ft_print_tables_fd.c\
	ft_strcmp.c\
	ft_strncpy.c\
	ft_lstiter.c\
	ft_putchar.c\
	ft_strcpy.c\
	ft_strnequ.c\

OBJ = $(SRC:.c=.o)

all: $(NAME)

$(NAME): $(OBJ)
	ar sur $@ $^

%.o: %.c
	gcc -c $< $(FLAG)

clean:
	rm -f $(OBJ)


fclean: clean
	rm -f $(NAME)

re: fclean all
