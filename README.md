# SectionNExpression

-p = directory should contain a file called "section_datasets_metadata.csv" and subdirs for all datasets
     each subdir should have an alignment json, a metadata json and directores called "expression_images" and "section_images"

-a = directory should contain a file called "atlas_metadata.json" and subdirs for all atlases (e.g. E11.5, etc)
-o = where output will be stored

python SectionNExpression.py -p /project/picsl/jtduda/data/Allen/DevCCF/dev_markers_batch_v2/ -a /project/picsl/jtduda/data/Allen/DevCCF/atlas_models/ -o /project/picsl/jtduda/data/Allen/DevCCF/subjects_corrected_v2/

