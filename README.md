# vscodeSnippet
vscode 代码段保姆级demo
文档地址  https://www.cnblogs.com/byksj/p/14442183.html

{
	"log": {
		"scope": "javascript",
		"prefix": "log",
		"body": [
			"${1:this}.\\$delete( target, key )",
			"$2"
		],
		"description": "this包围"
	},
	"log1": {
		"scope": "javascript",
		"prefix": "log1",
		"body": [
			"${1|this,vm|}.\\$delete( target, key )",
		],
		"description": "this vim 选择"
	},
	"log2": {
		"scope": "javascript",
		"prefix": "log2",
		"body": [
			"${1|this,vm|}.\\$delete( target, key )",
			"${2|hhh,ttt|}"
		],
		"description": "只有一个生效"
	},
	"log3": {
		"scope": "javascript",
		"prefix": "log3",
		"body": [
			"\\$this",
		],
		"description": "$展示 $ 前面两个转义符号才会展示 "
	},
	"log4": {
		"scope": "javascript",
		"prefix": "log4",
		"body": [
			"<ThePlanOrg v-model=\"modelObj.parentId\" styleOption=\"width:300px\"></ThePlanOrg>",
		],
		"description": " 双引号需要转义 "
	},
	"log5": {
		"scope": "javascript",
		"prefix": "log5",
		"body": [
			"\ta",
			"\t\ta",
			"\t\t\ta",
		],
		"description": "  \t 我是tab "
	},
	"log6": {
		"scope": "javascript",
		"prefix": "log5",
		"body": [
			"\ra",
			"\r\ra",
			"\r\r\ra",
		],
		"description": "  \r 换行 "
	},
	"log7": {
		"scope": "javascript",
		"prefix": "log7",
		"body": [
			"\na",
			"\n\na",
			"\n\n\na",
		],
		"description": "  \n 换行 "
	},
	"log8": {
		"scope": "javascript",
		"prefix": [
			"log8",
			"log88"
		],
		"body": [
			"8888888888"
		],
		"description": " prefix 数组模式 多个单词触发"
	},
	"log9": {
		"scope": "javascript",
		"prefix": "log9",
		"body": [
			"$TM_SELECTED_TEXT :TM_SELECTED_TEXT 当前选择的文本或空字符串",
			"$TM_CURRENT_LINE :TM_CURRENT_LINE 当前行的内容",
			"$TM_CURRENT_WORD :TM_CURRENT_WORD  光标下的单词内容或空字符串",
			"$TM_LINE_INDEX :TM_LINE_INDEX 基于零索引的行号",
			"$TM_LINE_NUMBER   :TM_LINE_NUMBER 基于一索引的行号",
			"$TM_FILENAME :TM_FILENAME 当前文档的文件名",
			"$TM_FILENAME_BASE :TM_FILENAME_BASE 当前文档的文件名，不带扩展名",
			"$TM_DIRECTORY :TM_DIRECTORY 当前文档的目录",
			"$TM_FILEPATH :TM_FILEPATH 当前文档的完整文件路径",
			"$CLIPBOARD :CLIPBOARD 剪贴板中的内容",
			"$WORKSPACE_NAME :WORKSPACE_NAME 打开的工作空间或文件夹的名称",
			"$WORKSPACE_FOLDER :WORKSPACE_FOLDER 打开的工作空间或文件夹的路径",
			"$CURRENT_YEAR :CURRENT_YEAR 本年度",
			"$CURRENT_YEAR_SHORT :CURRENT_YEAR_SHORT 本年度的最后两位数字",
			"$CURRENT_MONTH :CURRENT_MONTH 以两位数字表示的月份（例如“ 02”）",
			"$CURRENT_MONTH_NAME :CURRENT_MONTH_NAME 月的全名（例如“七月”）",
			"$CURRENT_MONTH_NAME_SHORT :CURRENT_MONTH_NAME_SHORT 该月的简称（例如“ Jul”）",
			"$CURRENT_DATE :CURRENT_DATE 一个月中的某天",
			"$CURRENT_DAY_NAME :CURRENT_DAY_NAME 一天的名称（例如“周一”）",
			"$CURRENT_DAY_NAME_SHORT :CURRENT_DAY_NAME_SHORT 一天的简称（例如“ Mon”）",
			"$CURRENT_HOUR :CURRENT_HOUR 当前小时（24小时制）",
			"$CURRENT_MINUTE :CURRENT_MINUTE 当前分钟",
			"$CURRENT_SECOND :CURRENT_SECOND  当前秒",
			"$CURRENT_SECONDS_UNIX :CURRENT_SECONDS_UNIX 自Unix时代以来的秒数",
			"$BLOCK_COMMENT_START :BLOCK_COMMENT_START 输出示例：PHP/*或HTML<!--",
			"$BLOCK_COMMENT_END :BLOCK_COMMENT_END输出示例：PHP*/或HTML-- >",
			"$LINE_COMMENT :LINE_COMMENT 示例输出：在PHP中 //",
		],
		"description": "内置变量 "
	},
		"For Loop": {
			"prefix": [
				"fr",
				"fr-gjl"
			],
			"body": [
				"for (const ${2:element} of ${1:array}) {",
				"\t$0",
				"}"
			],
			"description": "我是简写"
		}
}
