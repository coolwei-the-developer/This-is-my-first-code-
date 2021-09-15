import sys
import pygame
from pygame.locals import *

pygame.init()

surface = pygame.display.set_mode((720, 720))
clock = pygame.time.Clock()
surfrect = surface.get_rect()
rect = pygame.Rect ((0, 0), (128, 128))
rect.center = (surfrect.w/ 2, surfrect.h/ 2)
touched = False	
while True:
	for ev in pygame.event.get():
		if ev.type == QUIT:
			pygame.quit()
							
