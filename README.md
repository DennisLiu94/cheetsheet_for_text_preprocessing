# cheetsheet_for_text_preprocessing
A ubuntu cheetsheet for text preprocessing, mainly in awk, sed or cut

cat $1 | pv | awk --field-separator=" " "{if (NF < 10) print}" > $2
