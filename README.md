# Ditto to DocLister Reference Tables

## Main parameters

| Ditto Parameter | Ditto Example | DocLister Parameter | DocLister Example | 
| ------------- | ------------- | ------------- | ------------- |
| config  | ``` &config=`CONFIG_NAME` ``` | :x: | :x: |
| dateFormat  | ``` &dateFormat=`%d.%m.%Y` ``` | :heavy_check_mark:  | :heavy_check_mark:  |
| dateSource  | ``` &dateSource=`pub_date` ``` | :heavy_check_mark:  | :heavy_check_mark:  |
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
| language  | ------------- | customLang | ------------- |
| noResults  | ``` &noResults=`<p>No results.</p>` ``` | noneTPL | ``` &noneTPL=`NoneTpl` ``` |
| orderBy  | ``` &orderBy=`pub_date DESC` ``` | :heavy_check_mark: | :heavy_check_mark: |
| parents  | ``` &parents=`2,12` ``` | :heavy_check_mark: | :heavy_check_mark: |
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
| enable request extender for display,tpl,sortDir,sortBy parameters | ``` &extenders=`request` &good=`display,tpl,sortDir,sortBy` ```  | ``` &extenders=`request` &requestActive=`display\|\|tpl\|\|sortDir:g:(ASC,DESC)\|\|sortBy:g:(*):int`  ``` |
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
| paginate  | ------------- | :heavy_check_mark: | ``` &paginate=`pages` ``` |
| paginateAlwaysShowLinks  | ------------- | PrevNextAlwaysShow | ``` &PrevNextAlwaysShow=`1` ``` |
| paginateSplitterCharacter  | ------------- | ------------- | ------------- |
| tplPaginateCurrentPage  | ------------- | TplCurrentPage | ------------- |
| tplPaginateNext  | ------------- | TplNextP | ------------- |
| tplPaginateNextOff  | ------------- | TplNextI | ------------- |
| tplPaginatePage  | ------------- | TplPage | ------------- |
| tplPaginatePrevious  | ------------- | TplPrevP | ------------- |
| tplPaginatePreviousOff  | ------------- | TplPrevI | ------------- |


## Templates

| Ditto Parameter | Ditto Example | DocLister Parameter | DocLister Example | 
| ------------- | ------------- | ------------- | ------------- |
| outerTpl  | ``` &outerTpl=`OuterTpl` ``` | ownerTPL | ``` &ownerTPL=`OwnerTpl` ``` |
| tpl  | ``` &tpl=`NewsTpl` ``` | :heavy_check_mark: | :heavy_check_mark: |
| tplAlt  | ------------- | ------------- | ------------- |
| tplCurrentDocument  | ------------- | ------------- | ------------- |
| tplFirst  | ------------- | ------------- | ------------- |
| tplLast  | ------------- | ------------- | ------------- |
