# Convert yolo annotations to xml 
Clone repository

%cd /content/Armenian_Car_Plates_Detect_DL/utils

!python convert_yolo_labeling_to_xml_voc.py \
--images {image_path} \
--annot_path {yolo_annot_path} \
--output {xml_output_path} \
--classes {class_names .txt}



