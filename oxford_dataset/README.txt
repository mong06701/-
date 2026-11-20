이 폴더 전체를 학생에게 전달하세요. 01_check_dataset.ipynb에서 사진/품종/마스크/머리 박스를 확인합니다.
metadata 한 행=이미지 한 장. CSV 경로는 이 폴더 기준입니다.
품종 label=0~36; species_label=0 cat/1 dog. 공식 Test는 보존했습니다.
마스크 값 0=배경,1=동물,2=미분류. /255 정규화를 하지 마세요.
머리 박스는 일부 이미지에만 있으며 전신 박스가 아닙니다.
출처: Oxford-IIIT Pet Dataset. 원본 안내와 목록은 annotations에 보존했습니다.
