# download danlock content definitions and instances:
    create gitana.json
    create folder ./data
    npx cloudcms-util export -g ./gitana/gitana.json -q blog:article --folder-path ./data

# upload to local docker:
    create gitana.json from local docker
    create folder ./data
    npx cloudcms-util import -g ./gitana/gitana.json -q blog:article --folder-path ./data

# register custom module
    see ./modules/README.md