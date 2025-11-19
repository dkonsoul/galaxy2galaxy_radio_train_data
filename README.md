# galaxy2galaxy_radio_train_data
The data to generate meerkat_3600 problem galaxy catalogue, sent by the original ShapeNet authors, used for the radio data generation. Original ShapeNet project: https://github.com/CosmoStat/ShapeDeconv/

# To train, using galaxy2galaxy radio branch:
Make sure you are using the radio_data branch from galaxy2galaxy fork https://github.com/fadinammour/galaxy2galaxy

```bash
cp catalogue_SFGs_complete_wide1.fits /tmp/t2t_datagencatalogue_SFGs_complete_wide1.fits
g2g-datagen --problem=meerkat_3600 --data_dir=~/data_dir_radio/
```
