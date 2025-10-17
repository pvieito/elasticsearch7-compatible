# AI Agents Instructions

## Deployment

1. Update version in `elasticsearch/_version.py`
2. Build distributions: `rm -rf dist/ build/ *.egg-info && python setup.py sdist bdist_wheel`
3. Upload to PyPI: `twine upload dist/*`
4. Commit, tag and push: `git commit -am "Release X.Y.Z" && git tag X.Y.Z && git push origin HEAD && git push --tags`
