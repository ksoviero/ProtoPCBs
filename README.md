# ProtoPCBs

This is a collection of solderable breadboards. There are six different varieties based on two dimensions. One is the number of rows of tie-points (16, 32, 64) and the other is whether or not it includes power rails. 

## Dimentions

All ProtoPCBs use 100 mil spacing between tie-points and 300 mil spacing in the center for allowing the use of DIP ICs. 

![Dimensions for ProtoPCB_16](https://github.com/ksoviero/ProtoPCBs/raw/master/Dimensions.png)

## Sending to a PCB Fab

If you would like to have one or more of these produced by your PCB fab of choice, then you're going to need to do the following:

Create ZIP File (e.g. ProtoPCB_32):

```
git clone https://github.com/ksoviero/ProtoPCBs.git
cd ProtoPCBs/ProtoPCB_32/out/
zip ProtoPCB_32.zip *
```

Then upload the resulting `ProtoPCB_32.zip` file to your PCB fab. 
