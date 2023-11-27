# Neural Style Transfer
Neural Style Transfer (NST) refers to a class of software algorithms that manipulate digital images, or videos, in order to adopt the appearance or visual style of another image. NST algorithms are characterized by their use of deep neural networks for the sake of image transformation. Common uses for NST are the creation of artificial artwork from photographs, for example by transferring the appearance of famous paintings to user-supplied photographs. Several notable mobile apps use NST techniques for this purpose, including DeepArt and Prisma.

# rewrite the paths for your own images and base folder
BASE = "./drive/MyDrive/neural-style-transfer"
CONTENT_IMAGE_PATH = os.path.join(BASE, "images", "content.jpeg")
STYLE_IMAGE_PATH = os.path.join(BASE, "images", "style.png")
