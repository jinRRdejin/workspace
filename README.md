 static String word = "Monday⑿Tues⑾day⑿Wednesday⑿Thursday⑿Friday⑿Chinese⑿⑿English⑿Math⑿English⑿⑿⑿⑿⑿⑿⑿⑿⑿⑿Music⑿⑿pe⑿⑿Science⑿⑿English⑿⑿⑿⑿⑿⑿Music⑿⑿⑿⑿⑿⑿Computer⑿⑿⑿⒀⒀⒀";
    static String cr = "1:1,1:1;1:1,2:2;1:1,3:3;1:1,4:4;1:1,5:5;2:2,1:1;2:2,2:2;2:2,3:3;2:2,4:4;2:2,5:5;3:3,1:1;3:3,2:2;3:3,3:3;3:3,4:4;3:3,5:5;4:4,1:1;4:4,2:2;4:4,3:3;4:4,4:4;4:4,5:5;5:5,1:1;5:5,2:2;5:5,3:3;5:5,4:4;5:5,5:5;6:6,1:1;6:6,2:2;6:6,3:3;6:6,4:4;6:6,5:5;7:7,1:1;7:7,2:2;7:7,3:3;7:7,4:4;7:7,5:5;8:8,1:1;8:8,2:2;8:8,3:3;8:8,4:4;8:8,5:5;";
    static String coordi = "38,53,177,55,176,112,38,110,215,52,359,53,359,109,215,109,393,50,572,50,571,108,393,107,599,49,743,50,742,107,598,106,797,48,913,51,911,108,797,105,36,133,172,133,171,189,36,188,415,126,540,125,540,186,415,187,626,124,722,124,721,183,626,183,792,124,918,124,917,183,792,183,806,271,912,272,911,327,806,326,253.977,348,317.87,348,317.87,396,253.977,396,611,349,746,351,745,406,610,404,43,420,164,419,164,477,43,478,226,490,333,491,332,547,226,545,20.7654,588,39.9334,588,39.9334,624,20.7654,624,405,569,565,569,565,626,405,625,920.067,594,934.443,594,934.443,624,920.067,624,";
  Table
  @SerializedName("tableCount")
    private int tableCount;
    @SerializedName("table")
    private List<TableContent> table;
  
  TableContent
    private int id;
    private List<TableCell> body;
    TableCell
    private int startRow;
    @SerializedName("endRow")
    private int endRow;
    @SerializedName("startColumn")
    private int startColumn;
    @SerializedName("endColumn")
    private int endColumn;
    @SerializedName("word")
    private String word;
    @SerializedName("tableBoxCoordinate")
    private List<Float[]> tableBoxCoordinate;
    tableBoxCoordinate
    private Float tl_x;
    private Float tl_y;
    private Float tr_x;
    private Float tr_y;
    private Float br_x;
    private Float br_y;
    private Float bl_x;
    private Float bl_y;
