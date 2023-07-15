# hackathon3_unimol_data
hackathon3_unimol_data用于存储Hackathon比赛的数据集。

* data_0715
该数据集总共包含3000个结构，包含1000个含4个水的U20铀酰团簇、1000个含6个水的U20铀酰团簇以及1000个含8个水的U20铀酰团簇。 

其中训练集包含2500个结构，分别存储在target_train.pkl, atoms_train.pkl, coordinates_train.pkl三个压缩文件中。其中target_train.pkl存储能量，atoms_train.pkl存储原子类型，coordinates_train.pkl存储原子坐标结构。测试集包含500个结构，分别存储在target_pred.pkl, atoms_pred.pkl, coordinates_pred.pkl三个压缩文件中, 这三个文件分别存储了能量、原子类型和原子坐标结构。
