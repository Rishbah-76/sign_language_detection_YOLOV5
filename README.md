# sign_language_detection_YOLOV5

# How To Run:
### On GoogleCollab
```bash

1) Open the 'Sign_Language_detection_yolov5.ipynb' on Google Collab
2) Just run every shell

```

### On local system
```bash
git clone https://github.com/ultralytics/yolov5.git
```
```bash
extract 'yolov5.zip' and replace the orignal cloned 'yolov5' content
```
```bash
### For Prediction:
python detect.py --weights ./yolov5/runs/train/yolov5m_results/weights/best.pt --img 416 --conf 0.5 --source ./Data/test/images
```
```bash
### For Training:
python train.py --img 416 --batch 16 --epochs 580 --data './Data/data.yaml' --cfg ./yolov5/models/custom_yolov5m.yaml --weights 'yolov5m.pt'  --name yolov5m_results  --cache
```

# Evaluation Metrices:
 <table>
  <tr>
    <td>Result Graph After Training:</td>
  </tr>
  <tr>
    <td><img src="evalutation/results_graph.jpg" ></td>
  </tr>
 </table>

### Tensorflow log/ Metric Graph:
 <table>
  <tr>
    <td>Tensorflow log: Metric</td>
    <td>Tensorflow log: Train</td>
  </tr>
  <tr>
    <td><img src="evalutation/tensorflowlog.jpg" ></td>
    <td><img src="evalutation/tensorflowlog2.jpg"> </td>
  </tr>
 </table>

  # Train Data: Evaluation
 <table>
  <tr>
    <td>Train Data With Ground Truth</td>
  </tr>
  <tr>
    <td><img   height="450" src="evalutation/train_data.jpg" ></td>
  </tr>
 </table>


  # Predicted Images:
  <table>
  <tr>
    <td>Alphabets</td>
    <td>Greetings</td>
  </tr>
  <tr>
    <td><img   height="450" src="evalutation\orignal _signs.jpg" ></td>
    <td><img   height="450" src="evalutation\orignal _signs2.jpg" ></td>
  </tr>
 </table>

 
 <table>
  <tr>
    <td>A</td>
    <td>B</td>
    <td>C</td>
    <td>D</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/A.jpg ></td>
    <td><img src=evalutation/predicted_img/B.jpg ></td>
    <td><img src=evalutation/predicted_img/C.jpg ></td>
    <td><img src=evalutation/predicted_img/D.jpg ></td>
  </tr>
 </table> 


 <table>
  <tr>
    <td>E</td>
    <td>F</td>
    <td>G</td>
    <td>H</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/E.jpg ></td>
    <td><img src=evalutation/predicted_img/F.jpg ></td>
    <td><img src=evalutation/predicted_img/G.jpg ></td>
    <td><img src=evalutation/predicted_img/H.jpg ></td>
  </tr>
 </table> 

 <table>
  <tr>
    <td>I</td>
    <td>J</td>
    <td>K</td>
    <td>L</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/I.jpg ></td>
    <td><img src=evalutation/predicted_img/J.jpg ></td>
    <td><img src=evalutation/predicted_img/K.jpg ></td>
    <td><img src=evalutation/predicted_img/L.jpg ></td>
  </tr>
 </table> 

 <table>
  <tr>
    <td>M</td>
    <td>N</td>
    <td>O</td>
    <td>P</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/M.jpg ></td>
    <td><img src=evalutation/predicted_img/N.jpg ></td>
    <td><img src=evalutation/predicted_img/O.jpg ></td>
    <td><img src=evalutation/predicted_img/P.jpg ></td>
  </tr>
 </table> 

 <table>
  <tr>
    <td>Q</td>
    <td>R</td>
    <td>S</td>
    <td>T</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/Q.jpg ></td>
    <td><img src=evalutation/predicted_img/R.jpg ></td>
    <td><img src=evalutation/predicted_img/S.jpg ></td>
    <td><img src=evalutation/predicted_img/T.jpg ></td>
  </tr>
 </table> 

 <table>
  <tr>
    <td>U</td>
    <td>V</td>
    <td>W</td>
    <td>X</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/U.jpg ></td>
    <td><img src=evalutation/predicted_img/V.jpg ></td>
    <td><img src=evalutation/predicted_img/W.jpg ></td>
    <td><img src=evalutation/predicted_img/X.jpg ></td>
  </tr>
 </table> 

 <table>
  <tr>
    <td>Y</td>
    <td>Z</td>
    <td>Thanks</td>
    <td>Please</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/Y.jpg ></td>
    <td><img src=evalutation/predicted_img/Z.jpg ></td>
    <td><img src=evalutation/predicted_img/Thanks.jpg ></td>
    <td><img src=evalutation/predicted_img/Please.jpg ></td>
  </tr>
 </table> 

 <table>
  <tr>
    <td>Hello</td>
    <td>IloveYou</td>
    <td>What</td>
    <td>Name</td>
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/Hello.jpg ></td>
    <td><img src=evalutation/predicted_img/IloveYou.jpg ></td>
    <td><img src=evalutation/predicted_img/What.jpg ></td>
    <td><img src=evalutation/predicted_img/Name.jpg ></td>
  </tr>
 </table> 


 <table>
  <tr>
    <td>Yes</td>
    <td>No</td>
    <!-- <td>Thanks</td>
    <td>Please</td> -->
  </tr>
  <tr>
    <td><img src=evalutation/predicted_img/Yes.jpg ></td>
    <td><img src=evalutation/predicted_img/No.jpg ></td>
    <!-- <td><img src=evalutation/predicted_img/Thanks.jpg ></td>
    <td><img src=evalutation/predicted_img/Please.jpg ></td> -->
  </tr>
 </table> 

```bash
Author : Rishabh
Contact: rbrishabh76@gmail.com
```
