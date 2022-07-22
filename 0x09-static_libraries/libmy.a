/*
** my_strncpy.c for my_strncpy in /home/saumon/sommer_j/my_strncpy
** 
** Made by SOMMER Julien
** Login   <sommer_j@etna-alternance.net>
** 
** Started on  Fri Oct 21 13:10:00 2016 SOMMER Julien
** Last update Fri Oct 28 15:04:28 2016 SOMMER Julien
*/

int	my_strlen(char *str);

char	*my_strncpy(char *dest, char *src, int n)
{
  int	i;
  int	len;

  len = my_strlen(src);
  i = 0;
  while (i < n)
    {
      if (i < len && src[i] != '\0')
	{
	  dest[i] = src[i];
	  i++;
	}
      else
	{
	  dest[i] = '\0';
	  i++;
	}
    }
  return (dest);
}
