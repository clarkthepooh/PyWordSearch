# pysearch
Object Oriented word search solver written in python

##install

pip install PyWordSearch

##import

import PyWordSearch as pws

##make word search

search ="""w l e o y p s v i u e u y s t w k b k u
c w p p q i d t l s d r m l d d h s p o
z a q s a x j p i h a o e a d h l f i g
n k u z x s q i s n f w v p s r a w l b
m w g o q u t m i p x s b u v u p j v u
v e g g o t i d z s p f c e y g f m i k
x g x d i e r r k h f y v m t l h r n b
h s u j l o b m i m n s d b d w t g p q
j e q a a a m t m j i b m x k z o m m e
k n l r v v c e l l o h f f c h m b o g
u s t l c j i r v t w l k w h r w v k q
j x o w o n j c x n a y v t g e x c r b
e d a k k q g m a p j l a m i w g r j f
a x d x i d g i a n v n a f c b o g j h
u y i p r i j b x a i j l b n b w j u t
m d e u a q k h j g x d x q c m h m u g
u x v c j x e r i e x u f b x f v x m m
o k d c z s d x p x o s b x i f m k z a
v c y h y h y b q n s k u u a k e q u q
e r o t x o e l l r x k n r i z i w d q"""

my_search = pws.WordSearch(search)

##add the words you are looking for

words = ['slap', 'flap', 'hello', 'cello', 'extraordinary', 'fkva']

my_search.Words(words)

##solve

solved_search = my_search.Solve()

for x in solved_search:
  print(x)
