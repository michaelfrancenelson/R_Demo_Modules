# get all the directory names, excluding the current directory
# find . -maxdepth 1 -type d -not -path '*/\.*' -not -path '.'
#
# full path (but includes current directory)
# find ~+ -maxdepth 1 -type d -not -path '*/\.*' -not -path '.'
#
# full path, excluding current directory
# find . -maxdepth 1 -type d -not -path '*/\.*' -not -path '.' | xargs realpath

for d in $(find -maxdepth 1 -type d -not -path '*/\.*' -not -path '.' | xargs realpath)
do
	cd $d
	echo current directory: $(pwd)
	# echo $(git branch)
	# echo $(git rev-parse --abbrev-ref HEAD)
	br=$(git rev-parse --abbrev-ref HEAD)
	# echo $br
	git add -A
	git commit -m "autosaving"
	git push origin $br
done
echo -e "finished"
sleep 10