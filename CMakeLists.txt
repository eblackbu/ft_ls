cmake_minimum_required(VERSION 3.15)
project(new_ls C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(libft)
include_directories(libft/ft_printf)

add_executable(new_ls
        libft/ft_printf/colored.c
        libft/ft_printf/floating.h
        libft/ft_printf/ft_itoa_base.c
        libft/ft_printf/ft_itoa_base_uns.c
        libft/ft_printf/ft_printf.c
        libft/ft_printf/ft_printf.h
        libft/ft_printf/get_format.c
        libft/ft_printf/helper_numbers.c
        libft/ft_printf/helper_numbers2.c
        libft/ft_printf/print_addr_helper.c
        libft/ft_printf/print_chars_helper.c
        libft/ft_printf/print_float.c
        libft/ft_printf/print_float2.c
        libft/ft_printf/print_ints_helper.c
        libft/ft_printf/print_percent_helper.c
        libft/ft_printf/print_uns_helper.c
        libft/ft_atoi.c
        libft/ft_bzero.c
        libft/ft_isalnum.c
        libft/ft_isalpha.c
        libft/ft_isascii.c
        libft/ft_isdigit.c
        libft/ft_isprint.c
        libft/ft_isspace.c
        libft/ft_itoa.c
        libft/ft_lstadd.c
        libft/ft_lstdel.c
        libft/ft_lstdelone.c
        libft/ft_lstiter.c
        libft/ft_lstmap.c
        libft/ft_lstnew.c
        libft/ft_memalloc.c
        libft/ft_memccpy.c
        libft/ft_memchr.c
        libft/ft_memcmp.c
        libft/ft_memcpy.c
        libft/ft_memdel.c
        libft/ft_memmove.c
        libft/ft_memset.c
        libft/ft_putchar.c
        libft/ft_putchar_fd.c
        libft/ft_putendl.c
        libft/ft_putendl_fd.c
        libft/ft_putnbr.c
        libft/ft_putnbr_fd.c
        libft/ft_putstr.c
        libft/ft_putstr_fd.c
        libft/ft_range.c
        libft/ft_remove_sstr.c
        libft/ft_strcat.c
        libft/ft_strchr.c
        libft/ft_strclr.c
        libft/ft_strcmp.c
        libft/ft_strcpy.c
        libft/ft_strdel.c
        libft/ft_strdup.c
        libft/ft_strequ.c
        libft/ft_striter.c
        libft/ft_striteri.c
        libft/ft_strjoin.c
        libft/ft_strlcat.c
        libft/ft_strlen.c
        libft/ft_strmap.c
        libft/ft_strmapi.c
        libft/ft_strncat.c
        libft/ft_strncmp.c
        libft/ft_strncpy.c
        libft/ft_strnequ.c
        libft/ft_strnew.c
        libft/ft_strnstr.c
        libft/ft_strrchr.c
        libft/ft_strrev.c
        libft/ft_strsplit.c
        libft/ft_strstr.c
        libft/ft_strsub.c
        libft/ft_strtrim.c
        libft/ft_tolower.c
        libft/ft_toupper.c
        libft/ft_wcount.c
        libft/get_next_line.c
        libft/get_next_line.h
        libft/libft.h
        acrights_helper.c
        arg_parser.c
        args.h
        comparators.c
        comparators_2.c
        del_from_lists.c
        errors.c
        ft_ls.h
        get_fileinfo_1.c
        get_fileinfo_2.c
        l_flag_helper1.c
        ls_with_l.c
        ls_without_l.c
        main.c
        rec_flag_helper.c
        t_file_helper.c
        utils.c
        utils2.c)
