# D2DL

## Main parameters

| Ditto Parameter | Ditto Example | DocLister Parameter | DocLister Example | 
| ------------- | ------------- | ------------- | ------------- |
| config  | ``` &config=`CONFIG_NAME` ``` | :x: | :x: |
| dateFormat  | ------------- | ------------- | ------------- |
| dateSource  | ------------- | ------------- | ------------- |
| debug  | ``` &debug=`1` ``` | :heavy_check_mark: | :heavy_check_mark: |
| depth  | ``` &depth=`3` ``` | :heavy_check_mark: | :heavy_check_mark: |
| display  | ``` &display=`10` ``` | :heavy_check_mark: | :heavy_check_mark: |
| documents  | ``` &documents=`25,32,108` ``` | :heavy_check_mark: | :heavy_check_mark: |
| extenders  | ``` &extenders=`request` ``` | :heavy_check_mark: | :heavy_check_mark: |
| format  | ------------- | ------------- | ------------- |
| hiddenFields  | ------------- | ------------- | ------------- |
| hideFolders  | ``` &hideFolders=`1` ``` | showParent | ``` &showParent=`0` ``` |
| hidePrivate  | ------------- | ------------- | ------------- |
| id  | ------------- | ------------- | ------------- |
| keywords  | ------------- | ------------- | ------------- |
| language  | ------------- | ------------- | ------------- |
| noResults  | ------------- | ------------- | ------------- |
| orderBy  | ------------- | ------------- | ------------- |
| parents  | ------------- | ------------- | ------------- |
| phx  | ------------- | ------------- | ------------- |
| randomize  | ------------- | ------------- | ------------- |
| removeChunk  | ------------- | ------------- | ------------- |
| save  | ------------- | ------------- | ------------- |
| seeThruUnpub  | ------------- | ------------- | ------------- |
| showInMenuOnly  | ``` &showInMenuOnly=`1` ``` | addWhereList | ``` &addWhereList=`hidemenu=0` ``` |
| showPublishedOnly  | ``` &showPublishedOnly=`1` ``` | addWhereList | ``` &addWhereList=`published=1` ``` |
| start  | ``` &start=`3` ``` | :heavy_check_mark: | :heavy_check_mark: |
| total  | ``` &total=`100` ``` | :heavy_check_mark: | :heavy_check_mark: |
| where  | ------------- | ------------- | ------------- |

#### More Extenders Examples
| Description | Ditto Example | DocLister Examples | 
| ------------- | ------------- | ------------- | 
| enable request extender for display,tpl,sortDir,sortBy parameters | ``` &extenders=`request` &good=`display,tpl,sortDir,sortBy` ```  | ``` &extenders=`request` &requestActive=`display||tpl||sortDir:g:(ASC,DESC)||sortBy:g:(*):int`  ``` |
| ------------- | ------------- | ------------- |  
| ------------- | ------------- | ------------- | 
| ------------- | ------------- | ------------- | 
| ------------- | ------------- | ------------- | 

## Filtering

| Ditto Parameter | Ditto Example | DocLister Parameter | DocLister Example | 
| ------------- | ------------- | ------------- | ------------- |
| filter  | ------------- | ------------- | ------------- |
| globalFilterDelimiter  | ------------- | ------------- | ------------- |
| localFilterDelimiter  | ------------- | ------------- | ------------- |

#### More Filtering Examples
| Description | Ditto Example | DocLister Example | 
| ------------- | ------------- | ------------- | 
| show news in homepage with tv selection | ``` &filter=`NewsInHOME,yes` ```  | ``` &filters=`AND(tv:NewsInHOME:is:yes)` ``` |
| ------------- | ------------- | ------------- |  
| ------------- | ------------- | ------------- | 
| ------------- | ------------- | ------------- | 
| ------------- | ------------- | ------------- | 

## Pagination

| Ditto Parameter | Ditto Example | DocLister Parameter | DocLister Example | 
| ------------- | ------------- | ------------- | ------------- |
| paginate  | ------------- | ------------- | ------------- |
| paginateAlwaysShowLinks  | ------------- | ------------- | ------------- |
| paginateSplitterCharacter  | ------------- | ------------- | ------------- |
| tplPaginateCurrentPage  | ------------- | ------------- | ------------- |
| tplPaginateNextOff  | ------------- | ------------- | ------------- |
| tplPaginatePage  | ------------- | ------------- | ------------- |
| tplPaginatePrevious  | ------------- | ------------- | ------------- |
| tplPaginatePreviousOff  | ------------- | ------------- | ------------- |


## Templates

| Ditto Parameter | Ditto Example | DocLister Parameter | DocLister Example | 
| ------------- | ------------- | ------------- | ------------- |
| outerTpl  | ------------- | ------------- | ------------- |
| tpl  | ``` &tpl=`NewsTpl` ``` | :heavy_check_mark: | :heavy_check_mark: |
| tplAlt  | ------------- | ------------- | ------------- |
| tplCurrentDocument  | ------------- | ------------- | ------------- |
| tplFirst  | ------------- | ------------- | ------------- |
| tplLast  | ------------- | ------------- | ------------- |
