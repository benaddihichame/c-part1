# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: hbenaddi <hbenaddi@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2024/10/02 12:22:32 by hbenaddi          #+#    #+#              #
#    Updated: 2024/10/02 12:24:20 by hbenaddi         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CPPCOMPILER = c++
CPPFLAGS = -Werror -Wextra -Wall -std=c++98
NAME = megaphone
RM = rm -rf

all: $(NAME)

$(NAME): $(NAME).cpp
	$(CPPCOMPILER) $(CPPFLAGS) -o $(NAME) $(NAME).cpp

clean :
	$(RM) $(NAME)

re : clean all