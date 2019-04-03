# Converter for ICS 3UI
# This is for assignment #1






import pygame
pygame.init()
white = (255, 255, 255)
X = 600
Y = 800
display_surface = pygame.display.set_mode((X, Y))
pygame.display.set_caption('dice number 2')
image = pygame.image.load(r'H:\profile\Desktop\dice_2-512.png')

done = False
while done == False:
    display_surface.fill(white)
    display_surface.blit(image, (0, 0))
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            done = True
    pygame.display.update()

pygame.quit()
quit()
