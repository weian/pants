python_library(
  name='exclude_string',
  sources=rglobs('*.py',
                 exclude=[
                   ['aaa.py', 'dir1/aaa.py']
                 ]
                ),
  dependencies=[
  ]
)

python_library(
  name='exclude_globs',
  sources=rglobs('*.py',
                 exclude=[
                   globs('*bb.py', 'dir1/dirdir1/*aa.py')
                 ]
                ),
  dependencies=[
  ]
)

python_library(
  name='exclude_rglobs',
  sources=rglobs('*.py',
                 exclude=[
                   rglobs('*b.py')
                 ]
                ),
  dependencies=[
  ]
)

python_library(
  name='exclude_zglobs',
  sources=rglobs('*.py',
                 exclude=[
                   zglobs('**/*b.py')
                 ]
                ),
  dependencies=[
  ]
)

python_library(
  name='exclude_composite',
  sources=rglobs('*.py',
                 exclude=[
                   ['aaa.py'],
                   zglobs('**/a.py')
                 ]
                ),
  dependencies=[
  ]
)
