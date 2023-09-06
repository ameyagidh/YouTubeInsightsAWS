# KafaTubeAnalyzer

kaggle dataset Link:- https://www.kaggle.com/datasets/datasnaek/youtube-new?resource=download

Uploading Data To S3 bucket

aws s3 cp . s3://youtube-insightsbucket-ameya/youtube/raw_statistics_reference_data/ --recursive --exclude "" --include ".json"
