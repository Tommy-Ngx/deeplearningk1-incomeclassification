# deeplearningk1-incomeclassification
Income Classification

MÔ TẢ DATASET

Bộ dữ liệu "Thu thập điều tra dân số" chứa dữ liệu về những người trưởng thành từ cuộc điều tra dân số của các quốc gia. Dữ liệu này được gắn nhãn với việc liệu thu nhập hàng năm của người đó cao hơn hay thấp hơn $50k. Mục tiêu là dự đoán thu nhập của một người có vượt quá $50k/ năm hay không dựa vào dữ liệu đã cho.

DỮ LIỆU BAO GỒM CÁC MỤC SAU:

train.csv: tệp dữ liệu để training mô hình .
test.csv: tệp dữ liệu test trên Kaggle.
sample_submission.csv: tệp mẫu kết quả nộp lên Kaggle (30% dữ liệu Public và 70% dữ liệu Private trên Leaderboard Score)
CÁC TRƯỜNG DỮ LIỆU

ID: mã ID của từng bản ghi
age: Tuổi
work_type: Loại công việc (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
final_weight: Trọng số cuối cùng
education: Trình độ giáo dục (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
total_education_yrs: Số năm đi học
marital_state: Tình trạng hôn nhân (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
job: Nghề nghiệp (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
status: Mối quan hệ (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
ethnicity: Chủng tộc (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
sex: Giới tính (M/F)
capital_gain: Thu nhập từ các khoản đầu tư ngoài lương.
capital_loss: Thua lỗ từ các khoản đầu tư ngoài lương.
hrs_per_week: Số giờ làm việc trong 1 tuần
nationality: Quốc tịch (US, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)
target_income: Mức thu nhập (0: <=$50k, 1: >$50k)
