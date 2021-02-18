# QRCode
import pyqrcode
import png
from pyqrcode import QRCode
QRString="" #Enter or paste any path here 
url=pyqrcode.create(QRString)
url.png('Desktop\\qr.png',scale=8)
