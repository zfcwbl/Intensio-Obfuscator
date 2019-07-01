# CHANGESLOG 

## 02-06-2019
- Version 1.0.0
- Repository created

## 07-06-2019
- Version 1.0.1
- Add `include_python_words.txt`
- Add `exclude_python_words.txt`
- Allow execute each obfuscation features separately
- Correcting spelling errors in README and commentaries
- Code improvement
- Adding rules to replacement of variables - classes - functions
- Adding rules to padding random scripts 
- Change one file example and multiple files example (larger project)
- README.md file improvement

## 15-06-2019
- Version 1.0.2
- Path change from `include_python_words.txt` path to `include/python/include_python_words.txt`
- Path change from `exclude_python_words.txt` path to `include/python/exclude_python_words.txt`
- Add a display tqdm bar progress  when  `-r --replace`, `-p --padding`, `-rm --remove` features are specified
- Correcting spelling errors in `intensio_replace.py`, `intensio_obfuscation.py`, `intensio_padding.py`, `intensio_remove.py`
- Improvement of the code by adding a better management of the display of the analyzed inputs/outputs and the variables/classes/functions found
- Delete `-f --onfile` and `-d --multiplefiles` parameters, henceforth it is necessary to pointed a directory that containt files to obfuscate


## 17-06-2019
- Version 1.0.3
- Add new feature `-rp --rprint` this parameter remove all print functions
- Change `-rm --remove` parameter to `-rc --rcommentaries` parameter to remove all commentaries
- Add `docs/recommendation.md` reference to all the best practices for using this tool
- Add `docs/malfunctions.md`  reference any known dysfunctions
- Add `docs/examples/python_example.md` to put all examples will follow shortly
- Code improvements
- Spelling errors

## 01-07-2019
- Version 1.0.4
- update `-rc --rcommentaries`, this parameter is henceforth by executed default
- remove `docs/malfunctions.md` reference any known dysfunctions, is merged with `docs/recommendation.md`
- add a copy of [Intensio-Obfuscator](https://github.com/Hnfull/Intensio-Obfuscator/tree/master/intensio/test/python/basic/output/Intensio-Obfuscator) project at obfuscation test, only obfuscation basic #5 issue
- add verbose mode `-v --verbose` #9 issue
- improvement of the handle and detect process to all features #11 issue
- update `-m --mixer` to `-m --mixerlevel`
- Code improvements
- Spelling errors