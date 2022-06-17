<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Icons</title>
    <style>
      .wrapper {
        max-width: 900px;
        margin: 0 auto;
      }
      .items {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(100px, auto));
        gap: 20px 10px;
      }

      .item {
        width: 100%;
        height: 50px;
        /* background-color: red; */
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      .ico {
        flex: 1 0 50%;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      .item span {
        font-size: 12px;
      }
    </style>
  </head>
  <body>
    <div class="wrapper">
      <div class="items">
        <div class="item">
          <div class="ico">
            <svg
              width="20px"
              height="20px"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M12 24C5.372 24 0 18.628 0 12S5.372 0 12 0s12 5.372 12 12-5.372 12-12 12zm-1.2-13.2H6v2.4h4.8V18h2.4v-4.8H18v-2.4h-4.8V6h-2.4v4.8z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">AddPlusIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M4.871 7.25H14V8.75H4.871L8.894 12.773L7.8335 13.8335L2 8L7.8335 2.1665L8.894 3.227L4.871 7.25Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">ArrowLeftFullIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 8 12"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M7 1L2.05 5.95 7 10.9"
                stroke="#023DA2"
                strokeWidth="{2}"
              />
            </svg>
          </div>
          <span class="title">ArrowLeftSmallIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 8 14"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                fillRule="evenodd"
                clipRule="evenodd"
                d="M.646.646a.5.5 0 000 .708L6.293 7 .646 12.646a.501.501 0 00.708.708l6-6a.5.5 0 000-.708l-6-6a.5.5 0 00-.708 0z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">ArrowRightIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M18.1703 3.8763C17.0019 2.7079 15.1075 2.7079 13.9391 3.8763L5.4389 12.3765C3.48921 14.3262 3.52556 17.4983 5.5194 19.4028C7.43794 21.2354 10.4649 21.2135 12.3569 19.3535L19.147 12.6778L20.5491 14.104L13.759 20.7797C11.0969 23.397 6.83756 23.4277 4.13796 20.849C1.3324 18.1692 1.28126 13.7057 4.02469 10.9623L12.5249 2.46209C14.4743 0.512636 17.635 0.512638 19.5845 2.46209C21.5339 4.41154 21.5339 7.57223 19.5845 9.52168L11.5881 17.5181C10.4099 18.6962 8.49975 18.6962 7.3216 17.5181C6.14409 16.3406 6.14335 14.4317 7.31994 13.2533L15.5708 4.98951L16.9862 6.40263L8.73525 14.6664C8.33868 15.0636 8.33893 15.707 8.73581 16.1039C9.13292 16.501 9.77675 16.501 10.1739 16.1039L18.1703 8.10747C19.3387 6.93906 19.3387 5.04471 18.1703 3.8763Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">AttachIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M13.7995 4.54545V15C13.7995 17.0091 12.3078 18.6364 10.4661 18.6364C8.62448 18.6364 7.13281 17.0091 7.13281 15V3.63636C7.13281 2.38182 8.06615 1.36364 9.21615 1.36364C10.3661 1.36364 11.2995 2.38182 11.2995 3.63636V13.1818C11.2995 13.6818 10.9245 14.0909 10.4661 14.0909C10.0078 14.0909 9.63281 13.6818 9.63281 13.1818V4.54545H8.38281V13.1818C8.38281 14.4364 9.31615 15.4545 10.4661 15.4545C11.6161 15.4545 12.5495 14.4364 12.5495 13.1818V3.63636C12.5495 1.62727 11.0578 0 9.21615 0C7.37448 0 5.88281 1.62727 5.88281 3.63636V15C5.88281 17.7636 7.93281 20 10.4661 20C12.9995 20 15.0495 17.7636 15.0495 15V4.54545H13.7995Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">AttachIcon2</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 13 14"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8.96956 3.47994V10.2754C8.96956 11.5813 7.99998 12.639 6.8029 12.639C5.60581 12.639 4.63623 11.5813 4.63623 10.2754V2.88903C4.63623 2.07357 5.2429 1.41175 5.9904 1.41175C6.7379 1.41175 7.34456 2.07357 7.34456 2.88903V9.09357C7.34456 9.41857 7.10081 9.68448 6.8029 9.68448C6.50498 9.68448 6.26123 9.41857 6.26123 9.09357V3.47994H5.44873V9.09357C5.44873 9.90903 6.0554 10.5708 6.8029 10.5708C7.5504 10.5708 8.15706 9.90903 8.15706 9.09357V2.88903C8.15706 1.58312 7.18748 0.525391 5.9904 0.525391C4.79331 0.525391 3.82373 1.58312 3.82373 2.88903V10.2754C3.82373 12.0718 5.15623 13.5254 6.8029 13.5254C8.44956 13.5254 9.78206 12.0718 9.78206 10.2754V3.47994H8.96956Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">AttachSmallIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 27 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path d="M21.333 16V5.333h-6.666V16L18 14l3.333 2z" fill="#000" />
              <path
                d="M24 0H2.667A2.675 2.675 0 000 2.667v24l5.333-5.334H24c1.467 0 2.667-1.2 2.667-2.666v-16C26.667 1.2 25.467 0 24 0zm0 18.667H5.333l-2.666 2.666V2.667H24v16z"
                fill="#000"
              />
            </svg>
          </div>
          <span class="title">BalloonMarkIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 18 19"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M17.6087 7.54343H0.391304C0.175304 7.54343 0 7.71873 0 7.93473V11.0652C0 11.2812 0.175304 11.4565 0.391304 11.4565H17.6087C17.8247 11.4565 18 11.2812 18 11.0652V7.93473C18 7.71873 17.8247 7.54343 17.6087 7.54343ZM17.2174 10.6739H0.782609V8.32604H17.2174V10.6739Z"
                fill="#023DA2"
              />
              <path
                d="M0.391304 5.19564H11.3478C11.5638 5.19564 11.7391 5.02033 11.7391 4.80433V1.6739C11.7391 1.4579 11.5638 1.28259 11.3478 1.28259H0.391304C0.175304 1.28259 0 1.4579 0 1.6739V4.80433C0 5.02033 0.175304 5.19564 0.391304 5.19564ZM0.782608 2.0652H10.9565V4.41303H0.782608V2.0652Z"
                fill="#023DA2"
              />
              <path
                d="M14.4783 13.8044H0.391304C0.175304 13.8044 0 13.9797 0 14.1957V17.3261C0 17.5421 0.175304 17.7174 0.391304 17.7174H14.4783C14.6943 17.7174 14.8696 17.5421 14.8696 17.3261V14.1957C14.8696 13.9797 14.6943 13.8044 14.4783 13.8044ZM14.087 16.9348H0.782609V14.587H14.087V16.9348Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">BarChart</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 13 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M11.5556 2H10.8333V0.5H9.38889V2H3.61111V0.5H2.16667V2H1.44444C0.642778 2 0.00722222 2.675 0.00722222 3.5L0 14C0 14.825 0.642778 15.5 1.44444 15.5H11.5556C12.35 15.5 13 14.825 13 14V3.5C13 2.675 12.35 2 11.5556 2ZM11.5556 14H1.44444V6.5H11.5556V14ZM11.5556 5H1.44444V3.5H11.5556V5ZM6.5 8.75H10.1111V12.5H6.5V8.75Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">CalendarIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 26 26"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M15.6 5.474V2.737h-5.2v2.737h5.2zM2.6 8.21v15.052h20.8V8.211H2.6zm20.8-2.737c1.443 0 2.6 1.218 2.6 2.737v15.052C26 24.783 24.843 26 23.4 26H2.6C1.157 26 0 24.782 0 23.263L.013 8.211c0-1.52 1.144-2.737 2.587-2.737h5.2V2.737C7.8 1.217 8.957 0 10.4 0h5.2c1.443 0 2.6 1.218 2.6 2.737v2.737h5.2z"
                fill="#000"
              />
            </svg>
          </div>
          <span class="title">CaseIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="13"
              viewBox="0 0 16 13"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8.42407 2.75111L8 2.0722L7.57593 2.75111L2.46393 10.9351L1.98616 11.7H2.888H13.112H14.0138L13.5361 10.9351L8.42407 2.75111ZM0.902124 12.3L8 0.943398L15.0979 12.3H0.902124Z"
                fill="currentColor"
                stroke="currentColor"
              />
            </svg>
          </div>
          <span class="title">ChangeBookSectionIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="14"
              height="14"
              viewBox="0 0 14 14"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M2.625 5.6875L6.125 10.0625L11.375 3.0625"
                stroke="#023DA2"
                strokeWidth="2"
              />
            </svg>
          </div>
          <span class="title">CheckboxIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="5"
              height="11"
              viewBox="0 0 5 11"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M4.80825e-07 11L5 5.5L0 0L4.80825e-07 11Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">ChevronIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              viewBox="64 64 896 896"
              focusable="false"
              data-icon="close"
              width="1em"
              height="1em"
              fill="currentColor"
              aria-hidden="true"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M563.8 512l262.5-312.9c4.4-5.2.7-13.1-6.1-13.1h-79.8c-4.7 0-9.2 2.1-12.3 5.7L511.6 449.8 295.1 191.7c-3-3.6-7.5-5.7-12.3-5.7H203c-6.8 0-10.5 7.9-6.1 13.1L459.4 512 196.9 824.9A7.95 7.95 0 00203 838h79.8c4.7 0 9.2-2.1 12.3-5.7l216.5-258.1 216.5 258.1c3 3.6 7.5 5.7 12.3 5.7h79.8c6.8 0 10.5-7.9 6.1-13.1L563.8 512z"
                fill="lightgray"
              />
            </svg>
          </div>
          <span class="title">CloseIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="18px"
              height="18px"
              viewBox="0 0 18 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M1.80029 14.7002L1.80029 0.299927L0.000258684 0.299927L0.000258055 14.7002L1.80029 14.7002Z"
                fill="#023DA2"
              />
              <path
                d="M18.0005 14.7001L18.0005 0.299866L16.2005 0.299866L16.2005 14.7001L18.0005 14.7001Z"
                fill="#023DA2"
              />
              <path
                d="M13.943 10.9999L15.0005 9.91715L12.623 7.49994L15.0005 5.08273L13.943 4.00756L10.5005 7.49994L13.943 10.9999ZM4.05799 3.99994L3.00049 5.08273L5.37799 7.49994L3.00049 9.91715L4.05799 10.9999L7.50049 7.49994L4.05799 3.99994Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">CollapseIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8 14C11.3137 14 14 11.3137 14 8C14 4.68629 11.3137 2 8 2C4.68629 2 2 4.68629 2 8C2 11.3137 4.68629 14 8 14Z"
                fill="currentColor"
                stroke="currentColor"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M5.33337 10.6666L6.66671 6.66659L10.6667 5.33325L9.33337 9.33325L5.33337 10.6666Z"
                fill="white"
              />
            </svg>
          </div>
          <span class="title">CompassIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="30"
              height="31"
              viewBox="0 0 30 31"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M11.85 9.94737V9.94724L11.855 4.15789C11.855 4.15787 11.855 4.15785 11.855 4.15783L11.855 4.15777L12.005 4.15789L11.85 9.94737ZM11.85 9.94737C11.85 10.6071 12.355 11.15 13 11.15H21C21.645 11.15 22.15 10.6071 22.15 9.94737V4.15789C22.15 3.49818 21.645 2.95526 21 2.95526H19.15M11.85 9.94737L19.15 2.95526M19.15 2.95526V2.05263C19.15 1.39292 18.645 0.85 18 0.85H16C15.355 0.85 14.85 1.39292 14.85 2.05263V2.95526H19.15ZM16.15 2.20263H17.85V2.95526H16.15V2.20263ZM20.85 9.79737H13.15V4.30789H20.85V9.79737Z"
                fill="black"
                stroke="black"
                strokeWidth="0.3"
              />
              <path
                d="M27.9937 13.8901C28.2501 13.4923 28.4 13.0141 28.4 12.5C28.4 11.1215 27.3234 10 26 10C24.6766 10 23.6 11.1215 23.6 12.5C23.6 13.0141 23.7499 13.4923 24.0063 13.8901C22.8085 14.6108 22 15.9584 22 17.5V20H30V17.5C30 15.9584 29.1916 14.6108 27.9937 13.8901ZM25.2 12.5C25.2 12.0405 25.5589 11.6667 26 11.6667C26.4411 11.6667 26.8 12.0405 26.8 12.5C26.8 12.9595 26.4411 13.3333 26 13.3333C25.5589 13.3333 25.2 12.9595 25.2 12.5ZM28.4 18.3333H23.6V17.5C23.6 16.1215 24.6766 15 26 15C27.3234 15 28.4 16.1215 28.4 17.5V18.3333Z"
                fill="black"
              />
              <path
                d="M19.9479 21.5C19.4477 26.2743 15.406 30 10.5 30C5.25628 30 0.999999 25.7437 1 20.5C1 15.594 4.72569 11.5523 9.5 11.0521L9.5 20.5L9.5 21.5L10.5 21.5L19.9479 21.5Z"
                stroke="black"
                strokeWidth="2"
              />
            </svg>
          </div>
          <span class="title">ComplexMeasureIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="13"
              height="13"
              viewBox="0 0 13 13"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M10 3.78905L9.295 3.08405L6.5 5.87905L3.705 3.08405L3 3.78905L5.795 6.58405L3 9.37905L3.705 10.084L6.5 7.28905L9.295 10.084L10 9.37905L7.205 6.58405L10 3.78905Z"
                fill="black"
              />
            </svg>
          </div>
          <span class="title">CrossCloseTabsIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                fill="currentColor"
                d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm5 11H7v-2h10v2z"
              />
            </svg>
          </div>
          <span class="title">DeleteIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="17"
              height="16"
              viewBox="0 0 17 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8.5 0C4.08217 0 0.5 3.58182 0.5 7.99965C0.5 12.4178 4.08217 16 8.5 16C12.9178 16 16.5 12.4178 16.5 7.99965C16.5 3.58182 12.9182 0 8.5 0ZM9.72293 12.3679C9.72293 13.0387 9.17362 13.5824 8.50349 13.5824C7.83301 13.5824 7.28406 13.0387 7.28406 12.3679V7.05435C7.28406 6.38387 7.83301 5.84015 8.50349 5.84015C9.17362 5.84015 9.72293 6.38352 9.72293 7.05435V12.3679ZM8.5 4.83688C7.76003 4.83688 7.16009 4.23694 7.16009 3.49732C7.16009 2.757 7.76003 2.15775 8.5 2.15775C9.23962 2.15775 9.83991 2.757 9.83991 3.49732C9.83991 4.23694 9.23962 4.83688 8.5 4.83688Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">DetailIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8 1L1 4.5L8 8L15 4.5L8 1Z"
                fill="currentColor"
                stroke="currentColor"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M1 8L8 11.5L15 8"
                stroke="currentColor"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M1 11.5L8 15L15 11.5"
                stroke="currentColor"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
            </svg>
          </div>
          <span class="title">DistributionsSubjectsIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 22 28"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M5.667 19.333h10.666V22H5.667v-2.667zm0-5.333h10.666v2.667H5.667V14zm8-13.333H3A2.675 2.675 0 00.333 3.333v21.334a2.663 2.663 0 002.654 2.666H19c1.467 0 2.667-1.2 2.667-2.666v-16l-8-8zm5.333 24H3V3.333h9.333V10H19v14.667z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">DocumentIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M5.85714 2.55542H4.42857C4.04969 2.55542 3.68633 2.71931 3.41842 3.01104C3.15051 3.30276 3 3.69843 3 4.11099V13.4444C3 13.857 3.15051 14.2526 3.41842 14.5444C3.68633 14.8361 4.04969 15 4.42857 15H11.5714C11.9503 15 12.3137 14.8361 12.5816 14.5444C12.8495 14.2526 13 13.857 13 13.4444V4.11099C13 3.69843 12.8495 3.30276 12.5816 3.01104C12.3137 2.71931 11.9503 2.55542 11.5714 2.55542H10.1429"
                fill="currentColor"
              />
              <path
                d="M5.85714 2.55542H4.42857C4.04969 2.55542 3.68633 2.71931 3.41842 3.01104C3.15051 3.30276 3 3.69843 3 4.11099V13.4444C3 13.857 3.15051 14.2526 3.41842 14.5444C3.68633 14.8361 4.04969 15 4.42857 15H11.5714C11.9503 15 12.3137 14.8361 12.5816 14.5444C12.8495 14.2526 13 13.857 13 13.4444V4.11099C13 3.69843 12.8495 3.30276 12.5816 3.01104C12.3137 2.71931 11.9503 2.55542 11.5714 2.55542H10.1429"
                stroke="currentColor"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M8.71432 1H7.28575C6.49677 1 5.85718 1.69645 5.85718 2.55557C5.85718 3.41469 6.49677 4.11114 7.28575 4.11114H8.71432C9.5033 4.11114 10.1429 3.41469 10.1429 2.55557C10.1429 1.69645 9.5033 1 8.71432 1Z"
                fill="white"
                stroke="currentColor"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M4.85718 8H4.86384"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M8 8L11 8"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="square"
                strokeLinejoin="round"
              />
              <path
                d="M4.85718 11.1111H4.86384"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M8 11L11 11"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="square"
                strokeLinejoin="round"
              />
              <path
                d="M4.85718 11.1111H4.86384"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
            </svg>
          </div>
          <span class="title">DocumentsIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M17 21.0003H7C6.46957 21.0003 5.96086 20.7896 5.58579 20.4145C5.21071 20.0394 5 19.5307 5 19.0003V5.00029C5 4.46986 5.16309 4.00878 5.58579 3.58608C6.00849 3.16338 6.46957 3.00029 7 3.00029C7 3.00029 13.2471 2.99963 17.2499 3.00029C17.9334 3.00041 18.2509 3.14425 18.6412 3.58608C19.0814 4.08435 19 5.25029 19 5.25029V19.0003C19 19.5307 18.7893 20.0394 18.4142 20.4145C18.0391 20.7896 17.5304 21.0003 17 21.0003Z"
                fill="#023DA2"
                stroke="#023DA2"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M9 7.5H15"
                stroke="white"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M9 13H15"
                stroke="white"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M13 17H15"
                stroke="white"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
          <span class="title">DocumentUploadIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M5.121 7.99999L8.8335 11.7125L7.773 12.773L3 7.99999L7.773 3.22699L8.8335 4.28749L5.121 7.99999Z"
                fill="currentColor"
              />
              <path
                d="M10.121 7.99999L13.8335 11.7125L12.773 12.773L8 7.99999L12.773 3.22699L13.8335 4.28749L10.121 7.99999Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">DoubleArrowLeftIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="27"
              height="24"
              viewBox="0 0 27 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M24.25 3.75052H14.5V1.50052C14.5 1.27702 14.401 1.06552 14.2285 0.923022C14.0575 0.780522 13.828 0.719022 13.612 0.764022L1.612 3.01402C1.2565 3.08002 1 3.38902 1 3.75052V20.2505C1 20.6105 1.2565 20.921 1.612 20.987L13.612 23.237C13.657 23.246 13.7035 23.2505 13.75 23.2505C13.924 23.2505 14.0935 23.1905 14.2285 23.078C14.401 22.9355 14.5 22.7225 14.5 22.5005V20.2505H24.25C24.664 20.2505 25 19.9145 25 19.5005V4.50052C25 4.08652 24.664 3.75052 24.25 3.75052ZM11.314 14.507C11.587 14.8175 11.5555 15.2915 11.2435 15.5645C11.101 15.689 10.9255 15.7505 10.75 15.7505C10.5415 15.7505 10.3345 15.6635 10.186 15.494L8.005 13.0025L6.0925 15.4625C5.944 15.6515 5.722 15.7505 5.5 15.7505C5.3395 15.7505 5.1775 15.6995 5.0395 15.593C4.7125 15.338 4.654 14.867 4.9075 14.54L6.9985 11.852L4.936 9.49402C4.663 9.18352 4.6945 8.70952 5.0065 8.43652C5.317 8.16352 5.7895 8.19352 6.0655 8.50702L7.9375 10.646L10.159 7.79002C10.414 7.46452 10.885 7.40452 11.212 7.65952C11.539 7.91302 11.5975 8.38402 11.3425 8.71252L8.9425 11.7965L11.314 14.507ZM23.5 18.7505H14.5V17.2505H16.75C17.164 17.2505 17.5 16.9145 17.5 16.5005C17.5 16.0865 17.164 15.7505 16.75 15.7505H14.5V14.2505H16.75C17.164 14.2505 17.5 13.9145 17.5 13.5005C17.5 13.0865 17.164 12.7505 16.75 12.7505H14.5V11.2505H16.75C17.164 11.2505 17.5 10.9145 17.5 10.5005C17.5 10.0865 17.164 9.75052 16.75 9.75052H14.5V8.25052H16.75C17.164 8.25052 17.5 7.91452 17.5 7.50052C17.5 7.08652 17.164 6.75052 16.75 6.75052H14.5V5.25052H23.5V18.7505Z"
                fill="currentColor"
              />
              <path
                d="M21.25 6.75049H19.75C19.336 6.75049 19 7.08649 19 7.50049C19 7.91449 19.336 8.25049 19.75 8.25049H21.25C21.664 8.25049 22 7.91449 22 7.50049C22 7.08649 21.664 6.75049 21.25 6.75049Z"
                fill="currentColor"
              />
              <path
                d="M21.25 9.75049H19.75C19.336 9.75049 19 10.0865 19 10.5005C19 10.9145 19.336 11.2505 19.75 11.2505H21.25C21.664 11.2505 22 10.9145 22 10.5005C22 10.0865 21.664 9.75049 21.25 9.75049Z"
                fill="currentColor"
              />
              <path
                d="M21.25 12.7505H19.75C19.336 12.7505 19 13.0865 19 13.5005C19 13.9145 19.336 14.2505 19.75 14.2505H21.25C21.664 14.2505 22 13.9145 22 13.5005C22 13.0865 21.664 12.7505 21.25 12.7505Z"
                fill="currentColor"
              />
              <path
                d="M21.25 15.7505H19.75C19.336 15.7505 19 16.0865 19 16.5005C19 16.9145 19.336 17.2505 19.75 17.2505H21.25C21.664 17.2505 22 16.9145 22 16.5005C22 16.0865 21.664 15.7505 21.25 15.7505Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">DownloadExcelIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 17 17"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M14.096 11.5v3h-12v-3h-2v3c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-3h-2zm-1-4l-1.41-1.41-2.59 2.58V.5h-2v8.17l-2.59-2.58-1.41 1.41 5 5 5-5z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">DownloadIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="12px"
              height="12px"
              viewBox="0 0 14 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M2.6056 13.75H0.75V11.8944L8.60103 4.04337L10.4566 5.89897L2.6056 13.75ZM13.2422 3.07755C13.2526 3.08794 13.2526 3.103 13.2422 3.1134L12.3494 4.00621L10.4938 2.1506L11.3866 1.2578C11.397 1.2474 11.4121 1.2474 11.4225 1.2578L13.2422 3.07755Z"
                stroke="currentColor"
                strokeWidth="1.5"
              />
            </svg>
          </div>
          <span class="title">EditPencilIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="20px"
              height="20px"
              viewBox="0 0 25 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M2.484 2.526h17.384v7.58h2.484v-7.58V0H0c0 .5.012 1.861.012 2.526L0 20.21v2.527h11.176V20.21H2.484V2.526zm22.153 12.986l-.882.896-2.632-2.678.881-.896a1.222 1.222 0 011.751 0l.882.896a1.273 1.273 0 010 1.781zm-4.396-.885l2.633 2.678L16.291 24H13.66v-2.678l6.582-6.695z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">EditTabloIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="37"
              height="36"
              viewBox="0 0 37 36"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <g clipPath="url(#clip0)">
                <rect
                  width="36"
                  height="36"
                  transform="translate(0.519287)"
                  fill="white"
                />
                <path
                  d="M0.519287 8C0.519287 3.58172 4.10101 0 8.51929 0H28.5193C32.9376 0 36.5193 3.58172 36.5193 8V28C36.5193 32.4183 32.9376 36 28.5193 36H8.51929C4.10101 36 0.519287 32.4183 0.519287 28V8Z"
                  fill="#E9E8E6"
                />
                <path
                  d="M25.7194 25.2609V17.4561L20.5632 20.3771C19.5858 20.9309 18.3953 20.9636 17.3886 20.4646L11.3193 17.4561V25.2609C11.3193 25.2609 13.7193 27.8563 18.5193 27.8619C23.3193 27.8674 25.7194 25.2609 25.7194 25.2609Z"
                  fill="white"
                />
                <path
                  d="M28.1785 12.9365V20.0446"
                  stroke="white"
                  strokeWidth="1.31836"
                />
                <path
                  d="M26.7063 20.2709C26.7063 19.4466 27.3779 18.7783 28.2063 18.7783C29.0347 18.7783 29.7063 19.4466 29.7063 20.2709V22.7587H26.7063V20.2709Z"
                  fill="white"
                />
                <path
                  d="M28.6238 12.2948L19.4199 8.13968C19.1671 8.02555 18.878 8.02113 18.6218 8.12747L8.6087 12.2833C7.80698 12.616 7.78355 13.7378 8.57068 14.1034L18.5822 18.7536C18.8608 18.8831 19.1837 18.8777 19.4579 18.7393L28.6633 14.0883C29.4111 13.7104 29.3875 12.6396 28.6238 12.2948Z"
                  fill="white"
                />
              </g>
              <defs>
                <clipPath id="clip0">
                  <rect
                    width="36"
                    height="36"
                    fill="white"
                    transform="translate(0.519287)"
                  />
                </clipPath>
              </defs>
            </svg>
          </div>
          <span class="title">EducationPortalIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="12"
              height="12"
              viewBox="0 0 130 130"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <g>
                <g>
                  <path
                    d="M7.308,85.264h107.188c4.037,0,7.309-3.271,7.309-7.31s-3.271-7.309-7.309-7.309H7.308C3.271,70.646,0,73.916,0,77.954
                 S3.271,85.264,7.308,85.264z"
                    fill="currentColor"
                  />
                  <path
                    d="M7.308,51.158h107.188c4.037,0,7.309-3.272,7.309-7.309c0-4.037-3.271-7.308-7.309-7.308H7.308
                 C3.271,36.541,0,39.812,0,43.849C0,47.886,3.271,51.158,7.308,51.158z"
                    fill="currentColor"
                  />
                </g>
              </g>
            </svg>
          </div>
          <span class="title">EqualIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="48"
              height="48"
              viewBox="0 0 48 48"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <circle cx="24" cy="24" r="24" fill="#023DA2" />
              <path d="M21 10.0061H27L26 30H22L21 10.0061Z" fill="white" />
              <circle cx="24" cy="36" r="3" fill="white" />
            </svg>
          </div>
          <span class="title">ExclamationPointCircleIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M23.25 3.75052H13.5V1.50052C13.5 1.27702 13.401 1.06552 13.2285 0.923022C13.0575 0.780522 12.828 0.719022 12.612 0.764022L0.612 3.01402C0.2565 3.08002 0 3.38902 0 3.75052V20.2505C0 20.6105 0.2565 20.921 0.612 20.987L12.612 23.237C12.657 23.246 12.7035 23.2505 12.75 23.2505C12.924 23.2505 13.0935 23.1905 13.2285 23.078C13.401 22.9355 13.5 22.7225 13.5 22.5005V20.2505H23.25C23.664 20.2505 24 19.9145 24 19.5005V4.50052C24 4.08652 23.664 3.75052 23.25 3.75052ZM10.314 14.507C10.587 14.8175 10.5555 15.2915 10.2435 15.5645C10.101 15.689 9.9255 15.7505 9.75 15.7505C9.5415 15.7505 9.3345 15.6635 9.186 15.494L7.005 13.0025L5.0925 15.4625C4.944 15.6515 4.722 15.7505 4.5 15.7505C4.3395 15.7505 4.1775 15.6995 4.0395 15.593C3.7125 15.338 3.654 14.867 3.9075 14.54L5.9985 11.852L3.936 9.49402C3.663 9.18352 3.6945 8.70952 4.0065 8.43652C4.317 8.16352 4.7895 8.19352 5.0655 8.50702L6.9375 10.646L9.159 7.79002C9.414 7.46452 9.885 7.40452 10.212 7.65952C10.539 7.91302 10.5975 8.38402 10.3425 8.71252L7.9425 11.7965L10.314 14.507ZM22.5 18.7505H13.5V17.2505H15.75C16.164 17.2505 16.5 16.9145 16.5 16.5005C16.5 16.0865 16.164 15.7505 15.75 15.7505H13.5V14.2505H15.75C16.164 14.2505 16.5 13.9145 16.5 13.5005C16.5 13.0865 16.164 12.7505 15.75 12.7505H13.5V11.2505H15.75C16.164 11.2505 16.5 10.9145 16.5 10.5005C16.5 10.0865 16.164 9.75052 15.75 9.75052H13.5V8.25052H15.75C16.164 8.25052 16.5 7.91452 16.5 7.50052C16.5 7.08652 16.164 6.75052 15.75 6.75052H13.5V5.25052H22.5V18.7505Z"
                fill="currentColor"
              />
              <path
                d="M20.25 6.75052H18.75C18.336 6.75052 18 7.08652 18 7.50052C18 7.91452 18.336 8.25052 18.75 8.25052H20.25C20.664 8.25052 21 7.91452 21 7.50052C21 7.08652 20.664 6.75052 20.25 6.75052Z"
                fill="currentColor"
              />
              <path
                d="M20.25 9.75052H18.75C18.336 9.75052 18 10.0865 18 10.5005C18 10.9145 18.336 11.2505 18.75 11.2505H20.25C20.664 11.2505 21 10.9145 21 10.5005C21 10.0865 20.664 9.75052 20.25 9.75052Z"
                fill="currentColor"
              />
              <path
                d="M20.25 12.7505H18.75C18.336 12.7505 18 13.0865 18 13.5005C18 13.9145 18.336 14.2505 18.75 14.2505H20.25C20.664 14.2505 21 13.9145 21 13.5005C21 13.0865 20.664 12.7505 20.25 12.7505Z"
                fill="currentColor"
              />
              <path
                d="M20.25 15.7505H18.75C18.336 15.7505 18 16.0865 18 16.5005C18 16.9145 18.336 17.2505 18.75 17.2505H20.25C20.664 17.2505 21 16.9145 21 16.5005C21 16.0865 20.664 15.7505 20.25 15.7505Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">ExelIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="18px"
              height="18px"
              viewBox="0 0 18 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M1.80029 14.7002L1.80029 0.299927L0.000258684 0.299927L0.000258055 14.7002L1.80029 14.7002Z"
                fill="#023DA2"
              />
              <path
                d="M18.0005 14.7002L18.0005 0.299927L16.2005 0.299927L16.2005 14.7002L18.0005 14.7002Z"
                fill="#023DA2"
              />
              <path
                d="M4.88715 7.68005L7.00049 5.26284L6.06049 4.18768L3.00049 7.68005L6.06049 11.1801L7.00049 10.0973L4.88715 7.68005ZM13.1138 7.68005L11.0005 10.0973L11.9405 11.1724L15.0005 7.68005L11.9405 4.18005L11.0005 5.26284L13.1138 7.68005Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">ExpandIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M9 7.2H7V9.6H4V11.2H7V13.6H9V11.2H12V9.6H9V7.2ZM10 0H2C0.9 0 0 0.72 0 1.6V14.4C0 15.28 0.89 16 1.99 16H14C15.1 16 16 15.28 16 14.4V4.8L10 0ZM14 14.4H2V1.6H9V5.6H14V14.4Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">FileAddPlusIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 22 22"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M11.0007 16.1667L11.0007 21.3333L0.667321 11L11.0007 0.666663L11.0007 5.83333L21.334 5.83333L21.334 16.1667L11.0007 16.1667Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">FilledArrowLeft</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="17"
              height="22"
              viewBox="0 0 17 22"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M17 0H0V2.75L9.20833 11L0 19.25V22H17V17.875H7.08333L14.1667 11L7.08333 4.125H17V0Z"
                fill="#023DA2"
                stroke="currentColor"
              />
            </svg>
          </div>
          <span class="title">FillFinanceAmountsIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="15"
              height="15"
              viewBox="0 0 12 12"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M10.7148 0.775233L7.08558 5.49917H6.81228V5.99917V11.2518V11.2844L6.81653 11.3168C6.8241 11.3745 6.80121 11.4206 6.78198 11.4384L6.77364 11.4462L6.76567 11.4543C6.70566 11.5152 6.61319 11.5152 6.55317 11.4543L5.23433 10.1145C5.19014 10.0696 5.1781 10.0166 5.18317 9.97923L5.18772 9.94575V9.91196V5.99917V5.49917H4.91442L1.28515 0.775233L1.28516 0.775227L1.28323 0.772746C1.23176 0.706611 1.24049 0.600286 1.30779 0.541114C1.35937 0.5044 1.39197 0.5 1.40701 0.5H10.593C10.608 0.5 10.6406 0.504401 10.6922 0.541117C10.7595 0.60029 10.7682 0.706613 10.7168 0.772746L10.7148 0.775233Z"
                stroke="currentColor"
              />
            </svg>
          </div>
          <span class="title">FilterIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M2.29592 12.9407H4.36679V14.8773C4.36679 14.9715 4.39443 15.0487 4.45003 15.109C4.50548 15.1697 4.57636 15.2 4.66271 15.2H6.20652C6.28664 15.2 6.35597 15.1697 6.41453 15.109C6.47309 15.0487 6.50228 14.9715 6.50228 14.8773V12.9407H11.1709C11.2571 12.9407 11.328 12.9107 11.3836 12.8501C11.4392 12.7894 11.4668 12.7122 11.4668 12.618V11.3271C11.4668 11.2334 11.4392 11.1557 11.3836 11.0954C11.3281 11.0347 11.2571 11.0044 11.1709 11.0044H6.50213V9.81428H9.64537C10.8779 9.81428 11.8839 9.40456 12.6638 8.58395C13.4434 7.7642 13.8333 6.70528 13.8333 5.40714C13.8333 4.10986 13.4434 3.05092 12.6638 2.23033C11.8841 1.41056 10.8779 1 9.64537 1H4.66256C4.57618 1 4.50545 1.03031 4.44988 1.09063C4.39443 1.15129 4.36664 1.22895 4.36664 1.32265V7.66641H2.29592C2.20957 7.66641 2.13881 7.69828 2.08324 7.76214C2.02781 7.82602 2 7.90165 2 7.98903V9.49157C2 9.5858 2.02763 9.66299 2.08324 9.72362C2.13884 9.7843 2.20941 9.81425 2.29592 9.81425H4.36679V11.0044H2.29592C2.20957 11.0044 2.13881 11.0347 2.08324 11.0954C2.02781 11.1557 2 11.2332 2 11.327V12.618C2 12.7122 2.02763 12.7894 2.08324 12.85C2.13881 12.9107 2.20954 12.9407 2.29592 12.9407ZM6.50213 3.14837H9.46047C10.1137 3.14837 10.6406 3.35672 11.0413 3.77357C11.4418 4.19045 11.6422 4.73523 11.6422 5.40731C11.6422 6.07972 11.4418 6.62467 11.0413 7.04104C10.6406 7.45825 10.1137 7.6666 9.46047 7.6666H6.50213V3.14837Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">FinanceIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M15.8137 7.64038C15.5706 7.24829 15.1409 7.01392 14.6643 7.01392H4.05298C3.52698 7.01392 3.04859 7.31042 2.83386 7.76953L0.0272217 13.6542C0.133179 14.0851 0.535645 14.407 1.01502 14.407H12.3047C12.7874 14.407 13.2285 14.134 13.4441 13.7022L15.87 8.83984C16.0615 8.45508 16.0403 8.00671 15.8137 7.64038Z"
                fill="currentColor"
              />
              <path
                d="M2.26257 6.86426C2.47705 6.40528 2.95557 6.10864 3.48169 6.10864H13.474V4.83057C13.474 4.30371 13.0295 3.875 12.4833 3.875H6.65686C6.64832 3.875 6.64246 3.8728 6.64026 3.87122L5.59742 2.41309C5.41272 2.15442 5.10767 2 4.78174 2H0.990967C0.444458 2 0 2.42871 0 2.95557V11.6079L2.26257 6.86426Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">FolderIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 25 26"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M21.6754 14.208C21.7268 13.8225 21.7525 13.4241 21.7525 13C21.7525 12.5888 21.7268 12.1776 21.6626 11.792L24.2713 9.76164C24.5026 9.58173 24.5668 9.23476 24.4255 8.97774L21.9581 4.71131C21.8039 4.42859 21.4827 4.33863 21.1999 4.42859L18.1286 5.66226C17.4861 5.17393 16.805 4.76271 16.0468 4.45429L15.5842 1.19021C15.5328 0.881792 15.2758 0.66333 14.9673 0.66333H10.0327C9.72425 0.66333 9.48008 0.881792 9.42868 1.19021L8.96605 4.45429C8.20786 4.76271 7.51392 5.18678 6.88424 5.66226L3.81292 4.42859C3.5302 4.32578 3.20893 4.42859 3.05472 4.71131L0.600236 8.97774C0.446027 9.24761 0.49743 9.58173 0.754445 9.76164L3.36314 11.792C3.29889 12.1776 3.24748 12.6016 3.24748 13C3.24748 13.3984 3.27319 13.8225 3.33744 14.208L0.728743 16.2384C0.49743 16.4183 0.433177 16.7653 0.574535 17.0223L3.04187 21.2887C3.19608 21.5714 3.51735 21.6614 3.80006 21.5714L6.87139 20.3378C7.51392 20.8261 8.19501 21.2373 8.9532 21.5457L9.41583 24.8098C9.48008 25.1182 9.72425 25.3367 10.0327 25.3367H14.9673C15.2758 25.3367 15.5328 25.1182 15.5713 24.8098L16.0339 21.5457C16.7921 21.2373 17.4861 20.8261 18.1158 20.3378L21.1871 21.5714C21.4698 21.6742 21.7911 21.5714 21.9453 21.2887L24.4126 17.0223C24.5668 16.7396 24.5026 16.4183 24.2584 16.2384L21.6754 14.208ZM12.5 17.6263C9.95556 17.6263 7.87374 15.5445 7.87374 13C7.87374 10.4556 9.95556 8.37376 12.5 8.37376C15.0444 8.37376 17.1263 10.4556 17.1263 13C17.1263 15.5445 15.0444 17.6263 12.5 17.6263Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">GearIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M15.969 17.087a2.818 2.818 0 002.816-2.812 2.818 2.818 0 00-5.633 0 2.818 2.818 0 002.817 2.812zm0-3.75c.519 0 .941.421.941.938a.94.94 0 01-1.883 0 .94.94 0 01.942-.938z"
                fill="#000"
              />
              <path
                d="M.938 18.356h.972v12.706c0 .518.42.938.938.938h26.304c.518 0 .938-.42.938-.938V18.357h.973c.517 0 .937-.42.937-.937v-3.125c0-.391-.243-.741-.609-.878L16.938 8V5.625h4.523c.518 0 .938-.42.938-.938V.938A.937.937 0 0021.46 0H16a.938.938 0 00-.938.938V8L.61 13.416a.937.937 0 00-.609.878v3.125c0 .517.42.937.938.937zm8.457 11.769H7.512v-7.081c0-.517.42-.938.937-.938h.008c.517 0 .938.42.938.938v7.081zm5.632 0v-8.35c0-.517.42-.938.938-.938h.008c.517 0 .937.421.937.938v8.35h-1.883zm9.461 0h-1.882v-7.081c0-.517.42-.938.937-.938h.008c.517 0 .937.42.937.938v7.081zm-7.55-28.25h3.585V3.75h-3.585V1.875zM1.874 14.943L16 9.651l14.125 5.292v1.538h-9.154a.937.937 0 100 1.875h7.244v11.769h-1.852v-7.081a2.816 2.816 0 00-2.812-2.813h-.008a2.816 2.816 0 00-2.813 2.813v7.081h-1.945v-8.35a2.816 2.816 0 00-2.812-2.813h-.008a2.816 2.816 0 00-2.813 2.813v8.35H11.27v-7.081a2.816 2.816 0 00-2.812-2.813h-.008a2.816 2.816 0 00-2.812 2.813v7.081H3.785V18.356h7.181a.938.938 0 000-1.875H1.875v-1.538z"
                fill="#000"
              />
            </svg>
          </div>
          <span class="title">GovHouseIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 22 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M13.335 0H2.667A2.675 2.675 0 000 2.667v21.336a2.663 2.663 0 002.654 2.667h16.015c1.467 0 2.667-1.2 2.667-2.667V8.001L13.335 0zm5.334 24.003H2.667V2.667h9.335v6.668h6.667v14.668z"
                fill="#000"
              />
              <path
                d="M10.505 21.516a5.506 5.506 0 01-5.504-5.503 5.506 5.506 0 015.504-5.504v5.503h5.503a5.505 5.505 0 01-5.503 5.504z"
                fill="#000"
              />
            </svg>
          </div>
          <span class="title">GraphicsDocumentIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 30 31"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M11.85 9.947v0l.005-5.79s0 0 0 0h.15l-.155 5.79zm0 0c0 .66.505 1.203 1.15 1.203h8c.645 0 1.15-.543 1.15-1.203v-5.79c0-.659-.505-1.202-1.15-1.202h-1.85m-7.3 6.992l7.3-6.992m0 0v-.902c0-.66-.505-1.203-1.15-1.203h-2c-.645 0-1.15.543-1.15 1.203v.902h4.3zm-3-.752h1.7v.752h-1.7v-.752zm4.7 7.594h-7.7v-5.49h7.7v5.49z"
                fill="#fff"
                stroke="#fff"
                strokeWidth="{0.3}"
              />
              <path
                d="M27.994 13.89a2.56 2.56 0 00.406-1.39c0-1.379-1.077-2.5-2.4-2.5s-2.4 1.121-2.4 2.5c0 .514.15.992.406 1.39C22.808 14.61 22 15.958 22 17.5V20h8v-2.5c0-1.542-.808-2.89-2.006-3.61zM25.2 12.5c0-.46.359-.833.8-.833.441 0 .8.373.8.833 0 .46-.359.833-.8.833-.441 0-.8-.373-.8-.833zm3.2 5.833h-4.8V17.5c0-1.378 1.077-2.5 2.4-2.5s2.4 1.122 2.4 2.5v.833z"
                fill="#fff"
              />
              <path
                d="M19.948 21.5c-.5 4.774-4.542 8.5-9.448 8.5C5.256 30 1 25.744 1 20.5c0-4.906 3.726-8.948 8.5-9.448V21.5h10.448z"
                stroke="#fff"
                strokeWidth="{2}"
              />
            </svg>
          </div>
          <span class="title">GraphicsIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="18"
              height="19"
              viewBox="0 0 18 19"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M17.6087 7.54346H0.391304C0.175304 7.54346 0 7.71876 0 7.93476V11.0652C0 11.2812 0.175304 11.4565 0.391304 11.4565H17.6087C17.8247 11.4565 18 11.2812 18 11.0652V7.93476C18 7.71876 17.8247 7.54346 17.6087 7.54346ZM17.2174 10.6739H0.782609V8.32607H17.2174V10.6739Z"
                fill="currentColor"
              />
              <path
                d="M0.391304 5.19564H11.3478C11.5638 5.19564 11.7391 5.02033 11.7391 4.80433V1.6739C11.7391 1.4579 11.5638 1.28259 11.3478 1.28259H0.391304C0.175304 1.28259 0 1.4579 0 1.6739V4.80433C0 5.02033 0.175304 5.19564 0.391304 5.19564ZM0.782608 2.0652H10.9565V4.41303H0.782608V2.0652Z"
                fill="currentColor"
              />
              <path
                d="M14.4783 13.8043H0.391304C0.175304 13.8043 0 13.9796 0 14.1956V17.3261C0 17.5421 0.175304 17.7174 0.391304 17.7174H14.4783C14.6943 17.7174 14.8696 17.5421 14.8696 17.3261V14.1956C14.8696 13.9796 14.6943 13.8043 14.4783 13.8043ZM14.087 16.9348H0.782609V14.5869H14.087V16.9348Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">HamburgerIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="37"
              height="36"
              viewBox="0 0 37 36"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M0.736572 8C0.736572 3.58172 4.31829 0 8.73657 0H28.7366C33.1549 0 36.7366 3.58172 36.7366 8V28C36.7366 32.4183 33.1549 36 28.7366 36H8.73657C4.31829 36 0.736572 32.4183 0.736572 28V8Z"
                fill="#E9E8E6"
              />
              <path
                d="M18.7366 31C25.9163 31 31.7366 25.1797 31.7366 18C31.7366 10.8203 25.9163 5 18.7366 5C11.5569 5 5.7366 10.8203 5.7366 18C5.7366 25.1797 11.5569 31 18.7366 31Z"
                stroke="white"
                strokeWidth="2"
              />
              <path
                d="M18.7366 28C24.2595 28 28.7366 23.5228 28.7366 18C28.7366 12.4772 24.2595 8 18.7366 8C13.2138 8 8.7366 12.4772 8.7366 18C8.7366 23.5228 13.2138 28 18.7366 28Z"
                fill="#05C592"
              />
            </svg>
          </div>
          <span class="title">HeaderStatusIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="37"
              height="37"
              viewBox="0 0 37 37"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M0.945312 8.5C0.945312 4.08172 4.52703 0.5 8.94531 0.5H28.9453C33.3636 0.5 36.9453 4.08172 36.9453 8.5V28.5C36.9453 32.9183 33.3636 36.5 28.9453 36.5H8.94531C4.52703 36.5 0.945312 32.9183 0.945312 28.5V8.5Z"
                fill="#E9E9E9"
              />
              <path
                d="M12.896 12.5C12.896 9.19867 15.5947 6.5 18.896 6.5C22.1973 6.5 24.896 9.19867 24.896 12.5C24.896 15.8013 22.1973 18.5 18.896 18.5C15.5947 18.5 12.896 15.8013 12.896 12.5Z"
                fill="white"
              />
              <path
                d="M29.7316 23.5836C29.5925 23.3088 29.43 23.0474 29.2537 22.7993C27.9691 20.949 25.9863 19.7245 23.7521 19.4252C23.4728 19.398 23.1656 19.4523 22.9422 19.6156C21.7693 20.4592 20.3729 20.8945 18.9207 20.8945C17.4684 20.8945 16.0721 20.4592 14.8991 19.6156C14.6757 19.4523 14.3685 19.3707 14.0893 19.4252C11.8551 19.7245 9.84433 20.949 8.58762 22.7993C8.41839 23.0375 8.26181 23.3004 8.12643 23.5629C7.99941 23.8093 7.94531 24.0853 7.94531 24.3625V27.5C7.94531 28.6046 8.84074 29.5 9.94531 29.5H27.896C29.0006 29.5 29.896 28.6046 29.896 27.5V24.3368C29.896 24.0762 29.8493 23.816 29.7316 23.5836Z"
                fill="white"
              />
            </svg>
          </div>
          <span class="title">HeaderUserIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M18.346 8.158c.301-.45.478-.99.478-1.57A2.827 2.827 0 0016 3.765a2.827 2.827 0 00-2.823 2.823c0 .58.176 1.12.478 1.57a4.708 4.708 0 00-2.36 4.077v2.824h9.41v-2.824a4.707 4.707 0 00-2.36-4.077zm-3.287-1.57a.942.942 0 011.882 0 .942.942 0 01-1.882 0zm3.765 6.588h-5.648v-.94A2.827 2.827 0 0116 9.411a2.827 2.827 0 012.824 2.823v.941z"
                fill="#fff"
              />
              <path
                d="M29.64 25.1c.301-.45.478-.99.478-1.57a2.827 2.827 0 00-3.937-2.595l-2.943-3.188c1.92-1.88 3.115-4.5 3.115-7.394C26.353 4.644 21.709 0 16 0S5.647 4.644 5.647 10.353c0 2.894 1.194 5.514 3.115 7.394l-2.943 3.188a2.827 2.827 0 00-3.937 2.594c0 .581.177 1.121.478 1.57A4.708 4.708 0 000 29.177V32h9.412v-2.823a4.708 4.708 0 00-2.36-4.078 2.815 2.815 0 00.15-2.887l3.02-3.272A10.295 10.295 0 0016 20.706c2.138 0 4.126-.651 5.777-1.766l3.02 3.272a2.816 2.816 0 00.152 2.887 4.708 4.708 0 00-2.36 4.078V32H32v-2.823a4.708 4.708 0 00-2.36-4.078zM7.53 30.117H1.881v-.941a2.827 2.827 0 012.824-2.824 2.827 2.827 0 012.823 2.823v.942zm-3.765-6.589a.942.942 0 011.882 0 .942.942 0 01-1.882 0zm3.764-13.176c0-4.67 3.8-8.47 8.471-8.47 4.67 0 8.47 3.8 8.47 8.47 0 4.67-3.8 8.47-8.47 8.47-4.67 0-8.47-3.8-8.47-8.47zm18.824 13.176a.942.942 0 011.882 0 .942.942 0 01-1.882 0zm3.765 6.589H24.47v-.941a2.827 2.827 0 012.823-2.824 2.827 2.827 0 012.824 2.823v.942z"
                fill="#fff"
              />
            </svg>
          </div>
          <span class="title">HierRelationIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M1.16667 4H4.83333C5.47667 4 6 3.47667 6 2.83333V1.16667C6 0.523333 5.47667 0 4.83333 0H1.16667C0.523333 0 0 0.523333 0 1.16667V2.83333C0 3.47667 0.523333 4 1.16667 4Z"
                fill="currentColor"
              />
              <path
                d="M1.16667 10H4.83333C5.47667 10 6 9.47667 6 8.83333V7.16667C6 6.52333 5.47667 6 4.83333 6H1.16667C0.523333 6 0 6.52333 0 7.16667V8.83333C0 9.47667 0.523333 10 1.16667 10Z"
                fill="currentColor"
              />
              <path
                d="M1.16667 16H4.83333C5.47667 16 6 15.4767 6 14.8333V13.1667C6 12.5233 5.47667 12 4.83333 12H1.16667C0.523333 12 0 12.5233 0 13.1667V14.8333C0 15.4767 0.523333 16 1.16667 16Z"
                fill="currentColor"
              />
              <path
                d="M15.5 0.333252H7.83337C7.55737 0.333252 7.33337 0.557252 7.33337 0.833252C7.33337 1.10925 7.55737 1.33325 7.83337 1.33325H15.5C15.776 1.33325 16 1.10925 16 0.833252C16 0.557252 15.776 0.333252 15.5 0.333252Z"
                fill="currentColor"
              />
              <path
                d="M15.5 2.33325H7.83337C7.55737 2.33325 7.33337 2.55725 7.33337 2.83325C7.33337 3.10925 7.55737 3.33325 7.83337 3.33325H15.5C15.776 3.33325 16 3.10925 16 2.83325C16 2.55725 15.776 2.33325 15.5 2.33325Z"
                fill="currentColor"
              />
              <path
                d="M15.5 6.33325H7.83337C7.55737 6.33325 7.33337 6.55725 7.33337 6.83325C7.33337 7.10925 7.55737 7.33325 7.83337 7.33325H15.5C15.776 7.33325 16 7.10925 16 6.83325C16 6.55725 15.776 6.33325 15.5 6.33325Z"
                fill="currentColor"
              />
              <path
                d="M15.5 8.33325H7.83337C7.55737 8.33325 7.33337 8.55725 7.33337 8.83325C7.33337 9.10925 7.55737 9.33325 7.83337 9.33325H15.5C15.776 9.33325 16 9.10925 16 8.83325C16 8.55725 15.776 8.33325 15.5 8.33325Z"
                fill="currentColor"
              />
              <path
                d="M15.5 12.3333H7.83337C7.55737 12.3333 7.33337 12.5573 7.33337 12.8333C7.33337 13.1093 7.55737 13.3333 7.83337 13.3333H15.5C15.776 13.3333 16 13.1093 16 12.8333C16 12.5573 15.776 12.3333 15.5 12.3333Z"
                fill="currentColor"
              />
              <path
                d="M15.5 14.3333H7.83337C7.55737 14.3333 7.33337 14.5573 7.33337 14.8333C7.33337 15.1093 7.55737 15.3333 7.83337 15.3333H15.5C15.776 15.3333 16 15.1093 16 14.8333C16 14.5573 15.776 14.3333 15.5 14.3333Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">IndicatorsGPIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M2.375 7.5C2.75317 7.5 3.09546 7.34827 3.34839 7.10461L4.73596 7.79834C4.729 7.85486 4.71875 7.9104 4.71875 7.96875C4.71875 8.74414 5.34961 9.375 6.125 9.375C6.90039 9.375 7.53125 8.74414 7.53125 7.96875C7.53125 7.75232 7.47803 7.54968 7.39026 7.36633L9.27258 5.48401C9.45593 5.57178 9.65857 5.625 9.875 5.625C10.6504 5.625 11.2812 4.99414 11.2812 4.21875C11.2812 4.07275 11.2526 3.93469 11.2111 3.80225L12.8466 2.57593C13.0697 2.72498 13.3372 2.8125 13.625 2.8125C14.4004 2.8125 15.0312 2.18164 15.0312 1.40625C15.0312 0.630859 14.4004 0 13.625 0C12.8496 0 12.2188 0.630859 12.2188 1.40625C12.2188 1.55225 12.2474 1.69031 12.2889 1.82275L10.6534 3.04907C10.4303 2.90002 10.1628 2.8125 9.875 2.8125C9.09961 2.8125 8.46875 3.44336 8.46875 4.21875C8.46875 4.43518 8.52197 4.63782 8.60974 4.82117L6.72742 6.70349C6.54407 6.61572 6.34143 6.5625 6.125 6.5625C5.74683 6.5625 5.40454 6.71423 5.15161 6.95789L3.76404 6.26416C3.771 6.20764 3.78125 6.1521 3.78125 6.09375C3.78125 5.31836 3.15039 4.6875 2.375 4.6875C1.59961 4.6875 0.96875 5.31836 0.96875 6.09375C0.96875 6.86914 1.59961 7.5 2.375 7.5Z"
                fill="currentcolor"
              />
              <path
                d="M15.5312 15.0625H15.0312V5.15625C15.0312 4.89722 14.8215 4.6875 14.5625 4.6875H12.6875C12.4285 4.6875 12.2188 4.89722 12.2188 5.15625V15.0625H11.2812V7.96875C11.2812 7.70972 11.0715 7.5 10.8125 7.5H8.9375C8.67847 7.5 8.46875 7.70972 8.46875 7.96875V15.0625H7.53125V11.7188C7.53125 11.4597 7.32153 11.25 7.0625 11.25H5.1875C4.92847 11.25 4.71875 11.4597 4.71875 11.7188V15.0625H3.78125V9.84375C3.78125 9.58472 3.57153 9.375 3.3125 9.375H1.4375C1.17847 9.375 0.96875 9.58472 0.96875 9.84375V15.0625H0.46875C0.209717 15.0625 0 15.2722 0 15.5312C0 15.7903 0.209717 16 0.46875 16H15.5312C15.7903 16 16 15.7903 16 15.5312C16 15.2722 15.7903 15.0625 15.5312 15.0625Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">IndicatorsIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="30"
              height="30"
              viewBox="0 0 37 36"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M17.2363 13.5H20.2363V10.5H17.2363V13.5ZM18.7363 31C12.1213 31 6 24.615 6 18C6 11.385 12.1213 5.28516 18.7363 5.28516C25.3513 5.28516 31 11.385 31 18C31 24.615 25.3513 31 18.7363 31ZM18.7363 3C16.7665 3 14.816 3.38799 12.9961 4.14181C11.1762 4.89563 9.5226 6.00052 8.12973 7.3934C5.31668 10.2064 3.73633 14.0218 3.73633 18C3.73633 21.9782 5.31668 25.7936 8.12973 28.6066C9.5226 29.9995 11.1762 31.1044 12.9961 31.8582C14.816 32.612 16.7665 33 18.7363 33C22.7146 33 26.5299 31.4196 29.3429 28.6066C32.156 25.7936 33.7363 21.9782 33.7363 18C33.7363 16.0302 33.3483 14.0796 32.5945 12.2597C31.8407 10.4399 30.7358 8.78628 29.3429 7.3934C27.9501 6.00052 26.2965 4.89563 24.4766 4.14181C22.6567 3.38799 20.7062 3 18.7363 3ZM17.2363 25.5H20.2363V16.5H17.2363V25.5Z"
                fill="#727272"
              />
            </svg>
          </div>
          <span class="title">InformationHeaderIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 17 17"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8.278.5a8 8 0 100 16 8 8 0 000-16zM9.5 12.868a1.22 1.22 0 01-2.44 0V7.554a1.219 1.219 0 012.44 0v5.314zM8.278 5.337a1.34 1.34 0 110-2.68 1.34 1.34 0 010 2.68z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">InformationIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="15"
              height="16"
              viewBox="0 0 15 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M13.9558 8.86328C13.5186 8.86328 13.1321 9.14503 12.9973 9.56103C12.2683 11.8128 10.1548 13.4465 7.66325 13.4465C4.57007 13.4465 2.05345 10.9297 2.05345 7.83624C2.05345 5.35494 3.67371 3.24816 5.91164 2.51096C6.34375 2.36858 6.63653 1.96456 6.63653 1.50907C6.63653 1.18645 6.48215 0.883152 6.22145 0.693431C5.96075 0.503421 5.62483 0.449799 5.31806 0.548576C2.23645 1.54101 0 4.42937 0 7.83634C0 12.0622 3.4376 15.5 7.66323 15.5C11.0566 15.5 13.9352 13.2811 14.9384 10.2191C15.0416 9.90423 14.9875 9.55907 14.793 9.29067C14.5989 9.02243 14.2877 8.86328 13.9558 8.86328Z"
                fill="#023DA2"
              />
              <path
                d="M9.38619 2.50277C11.0896 3.05423 12.4376 4.39923 12.9931 6.10091C13.1315 6.52453 13.526 6.81057 13.9717 6.81057H13.9928C14.3147 6.81057 14.617 6.6567 14.8065 6.39674C14.9955 6.13681 15.0496 5.80165 14.9509 5.49538C14.1995 3.15873 12.3551 1.31059 10.0204 0.553637C9.71109 0.45341 9.37171 0.507269 9.10856 0.698492C8.84536 0.889979 8.68945 1.19583 8.68945 1.52136V1.5437C8.68935 1.98038 8.97104 2.36815 9.38619 2.50277Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">LegendCircle</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 15 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M13.9558 8.36327C13.5186 8.36327 13.1321 8.64501 12.9973 9.06101C12.2683 11.3128 10.1548 12.9465 7.66325 12.9465C4.57007 12.9465 2.05345 10.4296 2.05345 7.33622C2.05345 4.85493 3.67371 2.74814 5.91164 2.01094C6.34375 1.86856 6.63653 1.46454 6.63653 1.00906C6.63653 0.686431 6.48215 0.383137 6.22145 0.193416C5.96075 0.00340545 5.62483 -0.0502164 5.31806 0.0485607C2.23645 1.041 0 3.92935 0 7.33633C0 11.5622 3.4376 15 7.66323 15C11.0566 15 13.9352 12.7811 14.9384 9.71908C15.0416 9.40421 14.9875 9.05906 14.793 8.79066C14.5989 8.52242 14.2877 8.36327 13.9558 8.36327Z"
                fill="currentColor"
              />
              <path
                d="M9.38561 2.00273C11.0891 2.55419 12.437 3.89919 12.9925 5.60086C13.1309 6.02448 13.5254 6.31053 13.9711 6.31053H13.9923C14.3141 6.31053 14.6165 6.15665 14.8059 5.89669C14.995 5.63676 15.049 5.30161 14.9503 4.99533C14.1989 2.65869 12.3546 0.810546 10.0199 0.0535913C9.71051 -0.0466362 9.37113 0.00722292 9.10798 0.198446C8.84478 0.389934 8.68887 0.695786 8.68887 1.02131V1.04365C8.68877 1.48033 8.97046 1.8681 9.38561 2.00273Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">LegendStatusIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 14 14"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M9.91134 4.83341H9.36967V3.75008C9.36967 2.25508 8.15634 1.04175 6.66134 1.04175C5.16634 1.04175 3.953 2.25508 3.953 3.75008V4.83341H3.41134C2.8155 4.83341 2.328 5.32091 2.328 5.91675V11.3334C2.328 11.9292 2.8155 12.4167 3.41134 12.4167H9.91134C10.5072 12.4167 10.9947 11.9292 10.9947 11.3334V5.91675C10.9947 5.32091 10.5072 4.83341 9.91134 4.83341ZM6.66134 9.70842C6.0655 9.70842 5.578 9.22091 5.578 8.62508C5.578 8.02925 6.0655 7.54175 6.66134 7.54175C7.25717 7.54175 7.74467 8.02925 7.74467 8.62508C7.74467 9.22091 7.25717 9.70842 6.66134 9.70842ZM8.3405 4.83341H4.98217V3.75008C4.98217 2.82383 5.73509 2.07091 6.66134 2.07091C7.58759 2.07091 8.3405 2.82383 8.3405 3.75008V4.83341Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">LockIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="25"
              height="24"
              viewBox="0 0 25 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                fillRule="evenodd"
                clipRule="evenodd"
                d="M3.73633 5C3.73633 3.9 4.63633 3 5.73633 3H13.7363V5H5.73633V19H13.7363V21H5.73633C4.63633 21 3.73633 20.1 3.73633 19V5ZM17.9123 11L15.3763 8.464L16.7903 7.05L21.7403 12L16.7903 16.95L15.3763 15.536L17.9123 13H11.3263V11H17.9123Z"
                fill="#727272"
              />
            </svg>
          </div>
          <span class="title">LogoutIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="28"
              height="36"
              viewBox="0 0 37 36"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M28.2363 24.9231V25.3217L28.5106 25.611L31.7363 29.014V29.4615H5.73633V29.014L8.96208 25.611L9.23633 25.3217V24.9231V15.6923C9.23633 10.3164 11.9061 6.1065 16.3538 4.99477L17.1113 4.80543V4.02462V2.76923C17.1113 1.73813 17.8858 1 18.7363 1C19.5868 1 20.3613 1.73813 20.3613 2.76923V4.02462V4.80477L21.118 4.99457C25.5497 6.10615 28.2363 10.3358 28.2363 15.6923V24.9231ZM21.0574 33.3077C20.6795 34.3163 19.7508 35 18.7363 35C17.7104 35 16.7872 34.3176 16.4129 33.3077H21.0574Z"
                stroke="#727272"
                strokeWidth="2"
              />
            </svg>
          </div>
          <span class="title">MessageHeaderIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              width="18px"
              height="18px"
              viewBox="0 0 1024 1024"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                fill="white"
                d="M924.3 338.4a447.57 447.57 0 0 0-96.1-143.3 443.09 443.09 0 0 0-143-96.3A443.91 443.91 0 0 0 512 64h-2c-60.5.3-119 12.3-174.1 35.9a444.08 444.08 0 0 0-141.7 96.5 445 445 0 0 0-95 142.8A449.89 449.89 0 0 0 65 514.1c.3 69.4 16.9 138.3 47.9 199.9v152c0 25.4 20.6 46 45.9 46h151.8a447.72 447.72 0 0 0 199.5 48h2.1c59.8 0 117.7-11.6 172.3-34.3A443.2 443.2 0 0 0 827 830.5c41.2-40.9 73.6-88.7 96.3-142 23.5-55.2 35.5-113.9 35.8-174.5.2-60.9-11.6-120-34.8-175.6zM312.4 560c-26.4 0-47.9-21.5-47.9-48s21.5-48 47.9-48 47.9 21.5 47.9 48-21.4 48-47.9 48zm199.6 0c-26.4 0-47.9-21.5-47.9-48s21.5-48 47.9-48 47.9 21.5 47.9 48-21.5 48-47.9 48zm199.6 0c-26.4 0-47.9-21.5-47.9-48s21.5-48 47.9-48 47.9 21.5 47.9 48-21.5 48-47.9 48z"
              />
            </svg>
          </div>
          <span class="title">MessageIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="37"
              height="36"
              viewBox="0 0 37 36"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <g clipPath="url(#clip0_574_75)">
                <path
                  d="M0.736572 8C0.736572 3.58172 4.31829 0 8.73657 0H28.7366C33.1549 0 36.7366 3.58172 36.7366 8V28C36.7366 32.4183 33.1549 36 28.7366 36H8.73657C4.31829 36 0.736572 32.4183 0.736572 28V8Z"
                  fill="#E9E8E6"
                />
                <path
                  d="M31.918 18.4084L31.1054 16.9659C31.0441 16.8571 30.9305 16.7893 30.8065 16.7893H29.184C29.0614 16.7893 28.9478 16.8571 28.8851 16.9659L28.1744 18.2317H24.7056L27.5932 15.2697C27.7275 15.1319 27.7275 14.9079 27.5932 14.7701C27.4596 14.6322 27.2406 14.6322 27.1063 14.7701L23.7318 18.2317H22.2209L24.154 15.5206L20.8987 15.8839L21.6569 14.5368L26.2641 13.2696C26.4479 13.2187 26.5567 13.0251 26.5079 12.8364C26.459 12.6484 26.2703 12.541 26.0864 12.5862L22.1438 13.6711L23.8765 10.5931L24.4343 10.5917L24.5362 10.5931C24.5376 10.5931 24.5396 10.5931 24.5417 10.5931L25.302 10.5917C25.4246 10.5917 25.5382 10.5239 25.5995 10.415L26.4135 8.97255C26.4748 8.86442 26.4748 8.72802 26.4135 8.61918L25.5995 7.17669C25.5382 7.06856 25.4246 7 25.3006 7H23.6788C23.5555 7 23.4419 7.06856 23.3806 7.17669L22.5694 8.61918C22.5074 8.72802 22.5074 8.86442 22.5694 8.97255L23.2815 10.2384L21.5481 13.3191L20.4917 9.2701C20.4435 9.07998 20.2548 8.97467 20.0709 9.01991C19.8863 9.07079 19.7782 9.26515 19.8271 9.45173L21.0612 14.1827L20.3037 15.5284L18.9821 12.4547L17.6606 15.5291L16.903 14.182L18.1378 9.45527C18.1874 9.26586 18.0779 9.07291 17.894 9.02203C17.7122 8.97679 17.5215 9.08422 17.4726 9.27222L16.4161 13.3177L14.6828 10.2376L15.3949 8.97326C15.4561 8.86442 15.4561 8.72943 15.3949 8.61988L14.5836 7.1774C14.5223 7.06856 14.4087 7.00071 14.2861 7.00071H12.6622C12.539 7.00071 12.4253 7.06856 12.364 7.1774L11.5521 8.6213C11.4908 8.72943 11.4915 8.86442 11.5521 8.97326L12.364 10.4157C12.4253 10.5239 12.539 10.5924 12.6622 10.5924H13.4225C13.4232 10.5924 13.4239 10.5924 13.4246 10.5924L14.0864 10.591L15.8198 13.6725L11.8771 12.5876C11.6933 12.5431 11.5046 12.6505 11.4557 12.8378C11.4068 13.0272 11.5156 13.2201 11.6995 13.271L16.3073 14.5382L17.0656 15.8846L13.8102 15.5213L15.7433 18.231H14.2283L10.8559 14.7701C10.7216 14.6322 10.5033 14.6322 10.369 14.7701C10.2347 14.9072 10.2347 15.1319 10.369 15.269L13.2552 18.231H9.78842L9.07634 16.9652C9.01505 16.8564 8.90142 16.7886 8.77815 16.7886H7.15634C7.03376 16.7886 6.92013 16.8564 6.85815 16.9652L6.04621 18.4077C5.98492 18.5173 5.98492 18.6523 6.04621 18.7611L6.85746 20.2036C6.91875 20.3117 7.03238 20.3803 7.15565 20.3803L8.01511 20.3817C8.01649 20.3817 8.01855 20.3817 8.01993 20.3817L8.78022 20.3803C8.9028 20.3803 9.01643 20.3117 9.07772 20.2036L9.78911 18.9378H13.2545L10.369 21.8991C10.2347 22.0362 10.2347 22.2617 10.369 22.3988C10.4365 22.4687 10.5246 22.502 10.6128 22.502C10.7009 22.502 10.7891 22.4673 10.8565 22.3988L14.2289 18.9378H15.7454L13.8102 21.651L17.0649 21.2878L16.3087 22.6299L11.7002 23.8985C11.5163 23.9487 11.4075 24.1438 11.4564 24.331C11.506 24.5197 11.6947 24.6279 11.8778 24.5812L15.8218 23.4957L14.0878 26.5771L13.4225 26.5757L12.6622 26.5785C12.5396 26.5799 12.4267 26.6471 12.3654 26.7552L11.5542 28.1963C11.4922 28.3044 11.4922 28.4408 11.5542 28.5497L12.3661 29.9921C12.4274 30.1003 12.541 30.1688 12.6643 30.1688L13.5231 30.1702C13.5244 30.1702 13.5265 30.1702 13.5279 30.1702L14.2882 30.1688C14.4107 30.1688 14.5244 30.1003 14.5857 29.9921L15.3969 28.5497C15.4582 28.4408 15.4582 28.3044 15.3969 28.1963L14.6848 26.9312L16.4182 23.8504L17.476 27.898C17.5173 28.0563 17.6564 28.1588 17.8079 28.1588C17.8376 28.1588 17.8672 28.1546 17.8975 28.1461C18.0813 28.0966 18.1901 27.9002 18.1413 27.7143L16.9058 22.9875L17.664 21.6425L18.9856 24.7183L20.3064 21.644L21.0633 22.9861L19.8285 27.7143C19.7803 27.9044 19.8884 28.0966 20.0723 28.1461C20.1019 28.1546 20.1322 28.1588 20.1618 28.1588C20.3147 28.1588 20.4524 28.0556 20.493 27.898L21.5495 23.849L23.2842 26.9312L22.5708 28.197C22.5095 28.3072 22.5095 28.4415 22.5708 28.5504L23.3834 29.9929C23.4447 30.1017 23.5583 30.1695 23.6816 30.1695L24.4419 30.171C24.4432 30.171 24.4453 30.171 24.4467 30.171L25.3054 30.1695C25.4287 30.1695 25.5423 30.1017 25.6043 29.9929L26.4163 28.5504C26.4776 28.4415 26.4776 28.3058 26.4163 28.197L25.6043 26.7545C25.5423 26.6457 25.4287 26.5778 25.3054 26.5778H23.8827L22.1479 23.4971L26.0905 24.5819C26.2772 24.6286 26.4631 24.5197 26.512 24.3317C26.5609 24.1423 26.4521 23.9494 26.2682 23.8985L21.661 22.6313L20.9035 21.2856L24.1595 21.6503L22.2237 18.9378H23.7394L27.1111 22.3988C27.1786 22.4694 27.2668 22.502 27.3549 22.502C27.4431 22.502 27.5312 22.4673 27.5987 22.3988C27.7323 22.261 27.7323 22.0369 27.5987 21.8991L24.7139 18.9378H28.1799L28.8927 20.205C28.954 20.3124 29.0676 20.3817 29.1916 20.3817H30.8141C30.9374 20.3817 31.051 20.3124 31.1123 20.205L31.9242 18.7611C31.9793 18.653 31.9793 18.5173 31.918 18.4084ZM23.2615 8.79516L23.8751 7.70605H24.7201H25.1009L25.2917 8.04458L25.7145 8.79516L25.0995 9.88568H24.5403L24.4357 9.88427H24.2738L23.8765 9.88568L23.6774 9.53089L23.2615 8.79516ZM12.8592 7.70605L13.24 7.70463H13.5224L14.0843 7.70605L14.6972 8.79516L14.2833 9.52948L14.0843 9.88285L13.687 9.88427H12.8592L12.2463 8.79516L12.6691 8.04458L12.8592 7.70605ZM6.7397 18.5851L6.93046 18.2473L7.35261 17.4967H8.57844L8.99233 18.2325L9.19066 18.5858L8.99233 18.9392L8.57844 19.6756L7.35192 19.6742L6.92977 18.9244L6.7397 18.5851ZM14.6979 28.3765L14.0857 29.467L13.2331 29.4656H12.8599L12.6691 29.1271L12.247 28.3765L12.8599 27.2874L13.687 27.286H14.085L14.284 27.6394L14.6979 28.3765ZM25.1002 29.4656L24.727 29.467H24.4343H23.8751L23.2608 28.3765L23.6767 27.6408L23.8758 27.2874H24.2738H25.1016L25.7145 28.3765L25.293 29.1271L25.1002 29.4656ZM20.0482 20.4835L19.8753 20.8849L18.9807 22.9642L18.0862 20.8821L17.914 20.4821L17.4884 20.5301L15.2854 20.7761L16.5952 18.9385L16.8466 18.5865L16.5938 18.2317L15.2854 16.397L17.4898 16.643L17.9126 16.6896L18.0855 16.2882L18.9807 14.2068L19.8746 16.2882L20.0475 16.6896L20.4703 16.643L22.6754 16.397L21.367 18.2317L21.1149 18.5865L21.3656 18.9385L22.6754 20.7761L20.4717 20.5301L20.0482 20.4835ZM28.7701 18.5865L28.9691 18.2317L29.383 17.496H30.6089L31.031 18.2466L31.2204 18.5851L31.0317 18.9237L30.6095 19.6756H29.3844L28.9691 18.9385L28.7701 18.5865Z"
                  fill="black"
                />
              </g>
              <defs>
                <clipPath id="clip0_574_75">
                  <rect
                    width="36"
                    height="36"
                    fill="white"
                    transform="translate(0.736572)"
                  />
                </clipPath>
              </defs>
            </svg>
          </div>
          <span class="title">NewYearSupport</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="37"
              height="37"
              viewBox="0 0 37 37"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M0.945557 8.5C0.945557 4.08172 4.52728 0.5 8.94556 0.5H28.9456C33.3638 0.5 36.9456 4.08172 36.9456 8.5V28.5C36.9456 32.9183 33.3638 36.5 28.9456 36.5H8.94556C4.52728 36.5 0.945557 32.9183 0.945557 28.5V8.5Z"
                fill="#E9E9E9"
              />
              <path
                d="M31.783 17.7826C31.783 24.8422 26.06 29.9565 19.0004 29.9565C11.9407 29.9565 6.21777 24.8422 6.21777 17.7826C6.21777 10.723 11.9407 5 19.0004 5C26.06 5 31.783 10.723 31.783 17.7826Z"
                fill="white"
              />
              <path
                d="M23.1963 9.5097C22.5038 9.5097 21.9404 10.0731 21.9404 10.7655C21.9404 11.458 22.5038 12.0214 23.1963 12.0214C23.8888 12.0214 24.4521 11.458 24.4521 10.7655C24.4521 10.0731 23.8887 9.5097 23.1963 9.5097ZM23.1963 11.1652C22.976 11.1652 22.7967 10.9859 22.7967 10.7655C22.7967 10.5452 22.976 10.3659 23.1963 10.3659C23.4166 10.3659 23.5959 10.5452 23.5959 10.7655C23.5959 10.9859 23.4166 11.1652 23.1963 11.1652Z"
                fill="black"
              />
              <path
                d="M13.3202 13.6769C12.3759 13.6769 11.6077 14.4451 11.6077 15.3894C11.6077 16.3337 12.3759 17.102 13.3202 17.102C14.2645 17.102 15.0327 16.3337 15.0327 15.3894C15.0327 14.4451 14.2645 13.6769 13.3202 13.6769ZM13.3202 16.2457C12.848 16.2457 12.4639 15.8615 12.4639 15.3894C12.4639 14.9173 12.848 14.5331 13.3202 14.5331C13.7923 14.5331 14.1764 14.9172 14.1764 15.3894C14.1764 15.8616 13.7923 16.2457 13.3202 16.2457Z"
                fill="black"
              />
              <path
                d="M10.8083 20.527C10.1158 20.527 9.55249 21.0904 9.55249 21.7829C9.55249 22.4754 10.1159 23.0387 10.8083 23.0387C11.5008 23.0387 12.0642 22.4753 12.0642 21.7829C12.0642 21.0904 11.5008 20.527 10.8083 20.527ZM10.8083 22.1825C10.588 22.1825 10.4087 22.0032 10.4087 21.7829C10.4087 21.5625 10.588 21.3833 10.8083 21.3833C11.0287 21.3833 11.2079 21.5625 11.2079 21.7829C11.2079 22.0032 11.0287 22.1825 10.8083 22.1825Z"
                fill="black"
              />
              <path
                d="M25.5363 13.8481C24.592 13.8481 23.8237 14.6164 23.8237 15.5607C23.8237 16.505 24.592 17.2732 25.5363 17.2732C26.4806 17.2732 27.2488 16.505 27.2488 15.5607C27.2488 14.6164 26.4806 13.8481 25.5363 13.8481ZM25.5363 16.417C25.064 16.417 24.68 16.0329 24.68 15.5607C24.68 15.0886 25.0641 14.7045 25.5363 14.7045C26.0084 14.7045 26.3925 15.0886 26.3925 15.5607C26.3925 16.0329 26.0084 16.417 25.5363 16.417Z"
                fill="black"
              />
              <path
                d="M18.1723 7.16925C17.228 7.16925 16.4597 7.9375 16.4597 8.88179C16.4597 9.82608 17.228 10.5943 18.1723 10.5943C19.1165 10.5943 19.8848 9.82608 19.8848 8.88179C19.8848 7.9375 19.1166 7.16925 18.1723 7.16925ZM18.1723 9.73803C17.7001 9.73803 17.316 9.35391 17.316 8.88179C17.316 8.40967 17.7001 8.02555 18.1723 8.02555C18.6444 8.02555 19.0285 8.40967 19.0285 8.88179C19.0285 9.35391 18.6444 9.73803 18.1723 9.73803Z"
                fill="black"
              />
              <path
                d="M22.6816 20.5555H25.5834L20.0825 13.9544C20.3867 13.6668 20.577 13.2599 20.577 12.8092C20.577 11.9396 19.8696 11.2322 19.0001 11.2322C18.1305 11.2322 17.4231 11.9397 17.4231 12.8092C17.4231 13.2599 17.6135 13.6668 17.9177 13.9544L12.4167 20.5555H15.3185L12.4167 24.0377H15.3661L12.4167 27.577H25.5834L22.634 24.0377H25.5834L22.6816 20.5555ZM19.0001 12.0885C19.3975 12.0885 19.7208 12.4118 19.7208 12.8092C19.7208 13.2065 19.3975 13.5298 19.0001 13.5298C18.6027 13.5298 18.2794 13.2065 18.2794 12.8092C18.2794 12.4117 18.6027 12.0885 19.0001 12.0885ZM14.2449 19.6993L18.6972 14.3566C18.7953 14.3758 18.8965 14.3862 19.0001 14.3862C19.1038 14.3862 19.205 14.3758 19.3031 14.3566L23.7554 19.6993H14.2449ZM23.7553 26.7207H14.2449L16.4808 24.0377H21.5195L23.7553 26.7207ZM14.2449 23.1815L16.4332 20.5556H21.567L23.7553 23.1815H14.2449Z"
                fill="black"
              />
              <path
                d="M28.0824 8.76195C25.6566 6.33602 22.4311 5 19.0003 5C15.5696 5 12.3441 6.33602 9.9182 8.76195C7.49227 11.1879 6.15625 14.4132 6.15625 17.8441C6.15625 20.5921 7.01167 23.2131 8.63009 25.4236C9.78449 27.0005 11.2528 28.2729 12.9436 29.1754H11.0655V33H26.9351V29.1753H25.057C26.7478 28.2729 28.2161 27.0005 29.3705 25.4236C30.9889 23.213 31.8444 20.592 31.8444 17.844C31.8443 14.4132 30.5084 11.1878 28.0824 8.76195ZM26.0788 30.0316V32.1438H11.9218V30.0316H26.0788ZM22.9214 29.1753H20.5416V28.0907H19.6854V29.1753H18.3154V28.0907H17.4591V29.1753H15.0793C10.2491 27.5053 7.01255 22.9679 7.01255 17.844C7.01255 11.2339 12.3902 5.85624 19.0003 5.85624C25.6104 5.85624 30.9881 11.2339 30.9881 17.844C30.9881 22.9679 27.7515 27.5053 22.9214 29.1753Z"
                fill="black"
              />
              <path
                d="M14.4748 8.57532C12.9335 9.32492 11.5883 10.4585 10.5846 11.8535C9.56177 13.2753 8.91367 14.9447 8.71045 16.6811L9.5609 16.7806C9.74722 15.1883 10.3416 13.6575 11.2797 12.3536C12.2008 11.0733 13.4351 10.0331 14.8493 9.34532L14.4748 8.57532Z"
                fill="black"
              />
              <path
                d="M26.8779 21.7829C26.1854 21.7829 25.6221 22.3463 25.6221 23.0387C25.6221 23.7312 26.1855 24.2946 26.8779 24.2946C27.5704 24.2946 28.1338 23.7312 28.1338 23.0387C28.1338 22.3462 27.5704 21.7829 26.8779 21.7829ZM26.8779 23.4383C26.6576 23.4383 26.4783 23.2591 26.4783 23.0387C26.4783 22.8184 26.6576 22.6391 26.8779 22.6391C27.0982 22.6391 27.2775 22.8184 27.2775 23.0387C27.2775 23.2591 27.0982 23.4383 26.8779 23.4383Z"
                fill="black"
              />
            </svg>
          </div>
          <span class="title">NewYearUser</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="12"
              height="12"
              viewBox="0 0 130 130"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <g>
                <g>
                  <path
                    d="M7.308,75.519C3.271,75.519,0,78.789,0,82.827c0,4.036,3.271,7.31,7.308,7.31h18.897l-3.496,3.495
                  c-2.855,2.854-2.855,7.48,0,10.337c1.428,1.427,3.299,2.141,5.167,2.141c1.869,0,3.74-0.714,5.167-2.139l13.833-13.834h67.621
                  c4.037,0,7.31-3.272,7.31-7.31s-3.271-7.309-7.31-7.309H61.495L80.982,56.03h33.515c4.037,0,7.31-3.272,7.31-7.308
                  c0-4.037-3.271-7.309-7.31-7.309H95.602l13.24-13.24c2.854-2.855,2.854-7.481,0-10.336c-2.855-2.855-7.479-2.853-10.334,0
                  L74.932,41.414H7.308C3.271,41.414,0,44.685,0,48.723c0,4.036,3.271,7.308,7.308,7.308H60.31L40.821,75.519H7.308z"
                    fill="currentColor"
                  />
                </g>
              </g>
            </svg>
          </div>
          <span class="title">NotEqualIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="37"
              height="36"
              viewBox="0 0 37 36"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <g clipPath="url(#clip0)">
                <path
                  d="M0.736328 8C0.736328 3.58172 4.31805 0 8.73633 0H28.7363C33.1546 0 36.7363 3.58172 36.7363 8V28C36.7363 32.4183 33.1546 36 28.7363 36H8.73633C4.31805 36 0.736328 32.4183 0.736328 28V8Z"
                  fill="#E9E8E6"
                />
                <path
                  d="M20.0214 5.04126C16.1893 5.04126 12.6477 6.91777 10.4761 9.96529C11.0264 10.1208 11.5313 10.4142 11.9474 10.8299L12.3051 11.1876C14.0726 8.74317 16.9307 7.24054 20.0214 7.24054C25.2683 7.24054 29.5371 11.5093 29.5371 16.7564C29.5371 19.8624 28.0389 22.7112 25.5923 24.4748L25.8686 24.7511C26.3134 25.1962 26.6187 25.7457 26.7641 26.3393C29.8442 24.1751 31.7363 20.6285 31.7363 16.7564C31.7363 10.2966 26.481 5.04126 20.0214 5.04126Z"
                  fill="white"
                />
                <path
                  d="M21.6676 23.2588C21.3543 22.9455 20.9259 22.7886 20.4759 22.8338C19.6813 22.9141 18.936 23.22 18.3205 23.7184C18.2361 23.7874 18.1269 23.826 18.0146 23.826C17.9047 23.826 17.7972 23.7886 17.712 23.7208C15.9702 22.3187 14.3786 20.726 12.9799 18.9859C12.837 18.8095 12.8375 18.5521 12.9819 18.3749C13.479 17.761 13.7845 17.0162 13.8645 16.2221C13.909 15.7794 13.754 15.3449 13.4395 15.0301L10.5933 12.1842C10.3144 11.9056 9.94382 11.752 9.55007 11.752C9.5026 11.752 9.45384 11.7544 9.40538 11.7591C8.47334 11.8505 7.5934 12.2672 6.92831 12.9324C5.64947 14.2115 5.36659 16.2055 6.24054 17.7816C8.46659 21.8424 13.8201 27.6956 18.9276 30.4639C19.5211 30.7877 20.1942 30.9586 20.8749 30.9586C21.9569 30.9586 23.0106 30.5255 23.7659 29.7702C24.4311 29.1048 24.8479 28.2248 24.9393 27.2924C24.9827 26.8516 24.8276 26.4188 24.514 26.1048L21.6676 23.2588Z"
                  fill="white"
                />
                <path
                  d="M19.7192 9.75263C19.7192 9.33379 20.0588 8.99426 20.4776 8.99426C20.8964 8.99426 21.236 9.33379 21.236 9.75263V15.2129H26.2762C26.695 15.2129 27.0346 15.5524 27.0346 15.9713C27.0346 16.3901 26.695 16.7297 26.2762 16.7297H20.4776C20.0588 16.7297 19.7192 16.3901 19.7192 15.9713V9.75263Z"
                  fill="white"
                />
              </g>
              <defs>
                <clipPath id="clip0">
                  <rect
                    width="36"
                    height="36"
                    fill="white"
                    transform="translate(0.736328)"
                  />
                </clipPath>
              </defs>
            </svg>
          </div>
          <span class="title">OnTimeSupportIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8 0C3.584 0 0 3.584 0 8C0 12.416 3.584 16 8 16C12.416 16 16 12.416 16 8C16 3.584 12.416 0 8 0ZM10.888 5.072C11.744 5.072 12.432 5.76 12.432 6.616C12.432 7.472 11.744 8.16 10.888 8.16C10.032 8.16 9.344 7.472 9.344 6.616C9.336 5.76 10.032 5.072 10.888 5.072ZM6.088 3.808C7.128 3.808 7.976 4.656 7.976 5.696C7.976 6.736 7.128 7.584 6.088 7.584C5.048 7.584 4.2 6.736 4.2 5.696C4.2 4.648 5.04 3.808 6.088 3.808ZM6.088 11.112V14.112C4.168 13.512 2.648 12.032 1.976 10.144C2.816 9.248 4.912 8.792 6.088 8.792C6.512 8.792 7.048 8.856 7.608 8.968C6.296 9.664 6.088 10.584 6.088 11.112ZM8 14.4C7.784 14.4 7.576 14.392 7.368 14.368V11.112C7.368 9.976 9.72 9.408 10.888 9.408C11.744 9.408 13.224 9.72 13.96 10.328C13.024 12.704 10.712 14.4 8 14.4Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">OrganManagementIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M10.9091 4.36364C12.1164 4.36364 13.0836 3.38909 13.0836 2.18182C13.0836 0.974545 12.1164 0 10.9091 0C9.70182 0 8.72727 0.974545 8.72727 2.18182C8.72727 3.38909 9.70182 4.36364 10.9091 4.36364ZM5.09091 4.36364C6.29818 4.36364 7.26545 3.38909 7.26545 2.18182C7.26545 0.974545 6.29818 0 5.09091 0C3.88364 0 2.90909 0.974545 2.90909 2.18182C2.90909 3.38909 3.88364 4.36364 5.09091 4.36364ZM5.09091 5.81818C3.39636 5.81818 0 6.66909 0 8.36364V10.1818H10.1818V8.36364C10.1818 6.66909 6.78545 5.81818 5.09091 5.81818ZM10.9091 5.81818C10.6982 5.81818 10.4582 5.83273 10.2036 5.85455C11.0473 6.46545 11.6364 7.28727 11.6364 8.36364V10.1818H16V8.36364C16 6.66909 12.6036 5.81818 10.9091 5.81818Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">PeoplesIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M12 7.19972C16.1345 7.19972 19.8218 9.39058 21.6218 12.8569C19.8218 16.3231 16.1345 18.514 12 18.514C7.86545 18.514 4.17818 16.3231 2.37818 12.8569C4.17818 9.39058 7.86545 7.19972 12 7.19972ZM12 5.14258C6.54545 5.14258 1.88727 8.34144 0 12.8569C1.88727 17.3723 6.54545 20.5712 12 20.5712C17.4545 20.5712 22.1127 17.3723 24 12.8569C22.1127 8.34144 17.4545 5.14258 12 5.14258ZM12 10.2854C13.5055 10.2854 14.7273 11.4374 14.7273 12.8569C14.7273 14.2763 13.5055 15.4283 12 15.4283C10.4945 15.4283 9.27273 14.2763 9.27273 12.8569C9.27273 11.4374 10.4945 10.2854 12 10.2854ZM12 8.22829C9.29455 8.22829 7.09091 10.306 7.09091 12.8569C7.09091 15.4077 9.29455 17.4854 12 17.4854C14.7055 17.4854 16.9091 15.4077 16.9091 12.8569C16.9091 10.306 14.7055 8.22829 12 8.22829Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">PreviewIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="20px"
              height="20px"
              viewBox="0 0 19 17"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M18.278 4.944H.096v8h3.636V16.5h10.91v-3.556h3.636v-8zm-5.455 9.778H5.551v-4.444h7.272v4.444zM15.551 8.5c-.5 0-.91-.4-.91-.889s.41-.889.91-.889.909.4.909.89a.902.902 0 01-.91.888zm-.91-8H3.732v3.556h10.91V.5z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">PrintIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="48"
              height="48"
              viewBox="0 0 48 48"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                fillRule="evenodd"
                clipRule="evenodd"
                d="M48 24C48 30.3652 45.4714 36.4697 40.9706 40.9706C36.4697 45.4714 30.3652 48 24 48C17.6348 48 11.5303 45.4714 7.02944 40.9706C2.52856 36.4697 0 30.3652 0 24C0 17.6348 2.52856 11.5303 7.02944 7.02944C11.5303 2.52856 17.6348 0 24 0C30.3652 0 36.4697 2.52856 40.9706 7.02944C45.4714 11.5303 48 17.6348 48 24ZM19.71 18.099H15.75C15.66 12.441 20.04 10.5 24.018 10.5C28.209 10.5 32.037 12.69 32.037 17.22C32.037 20.46 30.132 22.002 28.305 23.391C26.094 25.068 25.275 25.695 25.275 27.849V28.914H21.351L21.33 27.525C21.216 24.744 22.815 23.031 24.834 21.564C26.604 20.232 27.729 19.356 27.729 17.451C27.729 14.976 25.845 13.947 23.787 13.947C21.084 13.947 19.713 15.756 19.713 18.099H19.71ZM23.463 37.428C21.711 37.428 20.436 36.246 20.436 34.647C20.436 32.991 21.711 31.827 23.466 31.827C25.293 31.827 26.55 32.991 26.55 34.647C26.55 36.246 25.29 37.428 23.463 37.428Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">QuestionCircleIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="15"
              height="15"
              viewBox="0 0 15 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path d="M5 13L10 7.5L5 2L5 13Z" fill="#023DA2" />
            </svg>
          </div>
          <span class="title">RightChevronIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="20px"
              height="20px"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M18.9596 0.292893C18.772 0.105357 18.5177 0 18.2525 0H2.66667C1.18667 0 0 1.2 0 2.66667V21.3333C0 22.8 1.18667 24 2.66667 24H21.3333C22.8 24 24 22.8 24 21.3333V5.74755C24 5.48233 23.8946 5.22798 23.7071 5.04044L18.9596 0.292893ZM12 21.3333C9.78667 21.3333 8 19.5467 8 17.3333C8 15.12 9.78667 13.3333 12 13.3333C14.2133 13.3333 16 15.12 16 17.3333C16 19.5467 14.2133 21.3333 12 21.3333ZM16 8H2.66667V2.66667H16V8Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">SaveIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 15 15"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M10.72 9.434h-.677l-.24-.232a5.55 5.55 0 001.346-3.627 5.574 5.574 0 10-5.574 5.574 5.55 5.55 0 003.627-1.346l.232.24v.677L13.722 15 15 13.722l-4.28-4.288zm-5.145 0a3.854 3.854 0 01-3.86-3.86 3.854 3.854 0 013.86-3.859 3.854 3.854 0 013.859 3.86 3.854 3.854 0 01-3.86 3.859z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">SearchIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <g opacity="0.7">
                <path
                  d="M20.6667 18.6667H19.6133L19.24 18.3067C20.5467 16.7867 21.3333 14.8133 21.3333 12.6667C21.3333 7.88 17.4533 4 12.6667 4C7.88 4 4 7.88 4 12.6667C4 17.4533 7.88 21.3333 12.6667 21.3333C14.8133 21.3333 16.7867 20.5467 18.3067 19.24L18.6667 19.6133V20.6667L25.3333 27.32L27.32 25.3333L20.6667 18.6667V18.6667ZM12.6667 18.6667C9.34667 18.6667 6.66667 15.9867 6.66667 12.6667C6.66667 9.34667 9.34667 6.66667 12.6667 6.66667C15.9867 6.66667 18.6667 9.34667 18.6667 12.6667C18.6667 15.9867 15.9867 18.6667 12.6667 18.6667Z"
                  fill="white"
                />
              </g>
            </svg>
          </div>
          <span class="title">SearchMagnifierIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              color="#1E58B0"
              {...props}
            >
              <path
                d="M15.6377 7.40491L0.988524 0.070419C0.873708 0.0129211 0.744741 -0.0101171 0.617152 0.00407857C0.489563 0.0182742 0.368792 0.0690985 0.269381 0.150432C0.174443 0.230106 0.103582 0.334718 0.064764 0.452509C0.0259457 0.570299 0.0207089 0.696597 0.0496425 0.817204L2.02063 7.99834L0.0230075 15.1595C-0.00414248 15.2602 -0.00731172 15.3659 0.0137547 15.4681C0.0348212 15.5702 0.0795356 15.666 0.144302 15.7477C0.209069 15.8294 0.292081 15.8948 0.386663 15.9386C0.481246 15.9823 0.584759 16.0032 0.688881 15.9996C0.793118 15.999 0.895753 15.9739 0.988524 15.9263L15.6377 8.59177C15.7468 8.53581 15.8383 8.4508 15.9023 8.3461C15.9662 8.24139 16 8.12106 16 7.99834C16 7.87562 15.9662 7.75528 15.9023 7.65058C15.8383 7.54588 15.7468 7.46087 15.6377 7.40491ZM1.72098 14.0726L3.19257 8.66511H8.67846C9.04671 8.66511 9.34524 8.36659 9.34524 7.99834C9.34524 7.63009 9.04671 7.33157 8.67846 7.33157H3.19257L1.72098 1.92404L13.8465 7.99834L1.72098 14.0726Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">SendIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M5.3335 7.11113L8.00016 9.7778L15.1113 2.66669"
                stroke="#C4C4C4"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M15.1109 8.00003V13.3334C15.1109 13.8049 14.9236 14.257 14.5902 14.5904C14.2568 14.9238 13.8046 15.1111 13.3331 15.1111H2.66645C2.19495 15.1111 1.74277 14.9238 1.40937 14.5904C1.07597 14.257 0.888672 13.8049 0.888672 13.3334V2.66669C0.888672 2.1952 1.07597 1.74301 1.40937 1.40961C1.74277 1.07622 2.19495 0.888916 2.66645 0.888916H10.6664"
                stroke="#C4C4C4"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
          <span class="title">SignedDocumentIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="20px"
              height="20px"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
              color="#1E58B0"
            >
              <path
                fillRule="evenodd"
                clipRule="evenodd"
                d="M12.8 1.597V0H3.2v1.597h9.6zM0 14.417h1.6V24H1a1 1 0 01-1-1v-8.582zm3.2 0h9.6V24H4.2a1 1 0 01-1-1v-8.582zM2 0v1.6H0V1a1 1 0 011-1h1zm10.8 3.238H3.2v9.582h9.6V3.238zm-12.8 0h1.6v9.582H0V3.238zm24-2.15a1 1 0 00-1-1h-8.6v1.596H24v-.597zm-9.6 13.33H24V23a1 1 0 01-1 1h-8.6v-9.582zM24 3.238h-9.6v9.582H24V3.238z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">SqTileIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M15 7.77778V2H10.1V4.16667H5.9V2H1V7.77778H5.9V5.61111H7.3V12.8333H10.1V15H15V9.22222H10.1V11.3889H8.7V5.61111H10.1V7.77778H15Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">StructureIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 31 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M19.556 2.7H14.85C14.337 1.134 12.589 0 11 0S7.663 1.134 7.15 2.7H2.444C1.1 2.7 0 3.915 0 5.4v18.9C0 25.785 1.1 27 2.444 27h17.112C20.9 27 22 25.785 22 24.3V5.4c0-1.485-1.1-2.7-2.444-2.7zM11 2.362c.501 0 1.1.46 1.1 1.013 0 .554-.599 1.013-1.1 1.013-.501 0-1.1-.46-1.1-1.013 0-.554.599-1.013 1.1-1.013zM19.556 24.3H2.444V5.4h17.112v18.9zM28.617 8.735h-3.998l-.01 15.483L26.628 27l1.98-2.73.01-15.535zM28.626 4.146c0-.52-.292-.923-.67-.923h-2.658c-.377 0-.67.403-.67.923v2.756h3.998V4.146z"
                fill="#fff"
              />
            </svg>
          </div>
          <span class="title">TabloIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 30 31"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M11.85 9.947v0l.005-5.79s0 0 0 0h.15l-.155 5.79zm0 0c0 .66.505 1.203 1.15 1.203h8c.645 0 1.15-.543 1.15-1.203v-5.79c0-.659-.505-1.202-1.15-1.202h-1.85m-7.3 6.992l7.3-6.992m0 0v-.902c0-.66-.505-1.203-1.15-1.203h-2c-.645 0-1.15.543-1.15 1.203v.902h4.3zm-3-.752h1.7v.752h-1.7v-.752zm4.7 7.594h-7.7v-5.49h7.7v5.49z"
                fill="#fff"
                stroke="#fff"
                strokeWidth="{0.3}"
              />
              <path
                d="M27.994 13.89a2.56 2.56 0 00.406-1.39c0-1.379-1.077-2.5-2.4-2.5s-2.4 1.121-2.4 2.5c0 .514.15.992.406 1.39C22.808 14.61 22 15.958 22 17.5V20h8v-2.5c0-1.542-.808-2.89-2.006-3.61zM25.2 12.5c0-.46.359-.833.8-.833.441 0 .8.373.8.833 0 .46-.359.833-.8.833-.441 0-.8-.373-.8-.833zm3.2 5.833h-4.8V17.5c0-1.378 1.077-2.5 2.4-2.5s2.4 1.122 2.4 2.5v.833z"
                fill="#fff"
              />
              <path
                d="M19.948 21.5c-.5 4.774-4.542 8.5-9.448 8.5C5.256 30 1 25.744 1 20.5c0-4.906 3.726-8.948 8.5-9.448V21.5h10.448z"
                stroke="#fff"
                strokeWidth="{2}"
              />
            </svg>
          </div>
          <span class="title">TeamIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="16"
              height="16"
              viewBox="0 0 16 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M8 8C10.21 8 12 6.21 12 4C12 1.79 10.21 0 8 0C5.79 0 4 1.79 4 4C4 6.21 5.79 8 8 8ZM8 10C5.33 10 0 11.34 0 14V16H16V14C16 11.34 10.67 10 8 10Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">TeamProgramIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="10"
              height="11"
              viewBox="0 0 5 17"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M2.411 4.78A2.136 2.136 0 01.278 2.64C.278 1.458 1.232.5 2.41.5c1.177 0 2.132.958 2.132 2.14 0 1.183-.955 2.14-2.132 2.14zM2.412 10.64A2.136 2.136 0 01.278 8.5c0-1.182.954-2.141 2.133-2.141 1.177 0 2.132.959 2.133 2.14-.001 1.184-.957 2.141-2.132 2.141zM2.412 16.5a2.136 2.136 0 01-2.134-2.14c0-1.184.954-2.141 2.133-2.141 1.177-.001 2.132.958 2.132 2.14 0 1.183-.956 2.141-2.131 2.141z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">ThreeDotsVerticalIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="10"
              height="12"
              viewBox="0 0 21 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M2.344 21.479c0 1.49 1.265 2.708 2.812 2.708h11.25c1.547 0 2.813-1.219 2.813-2.708V5.229H2.344v16.25zm3.46-9.642l1.982-1.91L10.78 12.8l2.981-2.871 1.983 1.91-2.98 2.87 2.98 2.87-1.982 1.91-2.982-2.87-2.981 2.87-1.983-1.91 2.981-2.87-2.995-2.87zm9.9-10.67L14.296-.189H7.266L5.859 1.166H.938v2.709h19.687V1.166h-4.922z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">TrashIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 15 29"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path d="M0 29l14.485-14.5L0 0v29z" fill="currentColor" />
            </svg>
          </div>
          <span class="title">TriangleRightIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 13 13"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M4.33301 11.2667L8.66634 6.5L4.33301 1.73334L4.33301 11.2667Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">TriangleRightSmallIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M4.1556 2.91961C6.33306 1.0328 9.11878 -0.00400783 12 1.16432e-05C18.6276 1.16432e-05 24 5.37241 24 12C24 14.5632 23.196 16.9392 21.828 18.888L18 12H21.6C21.6001 10.118 21.0471 8.27737 20.0096 6.70711C18.9721 5.13686 17.4959 3.9062 15.7646 3.16816C14.0333 2.43012 12.1232 2.21725 10.2719 2.55603C8.42063 2.89481 6.70974 3.77029 5.35199 5.07361L4.1556 2.91961ZM19.8444 21.0804C17.6669 22.9672 14.8812 24.004 12 24C5.3724 24 0 18.6276 0 12C0 9.4368 0.803999 7.0608 2.172 5.11201L5.99999 12H2.4C2.39984 13.882 2.9529 15.7226 3.9904 17.2929C5.0279 18.8631 6.50408 20.0938 8.23538 20.8318C9.96668 21.5699 11.8767 21.7827 13.728 21.444C15.5793 21.1052 17.2902 20.2297 18.648 18.9264L19.8444 21.0804Z"
                fill="currentColor"
              />
            </svg>
          </div>
          <span class="title">UpdateIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="22"
              height="22"
              viewBox="0 0 122 122"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M106.75 83.875V106.75H15.25V83.875H0V106.75C0 115.137 6.8625 122 15.25 122H106.75C115.137 122 122 115.137 122 106.75V83.875H106.75ZM22.875 38.125L33.6262 48.8762L53.375 29.2037V91.5H68.625V29.2037L88.3737 48.8762L99.125 38.125L61 0L22.875 38.125Z"
                fill="#023DA2"
              />
            </svg>
          </div>
          <span class="title">UploaderIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M17 21.0003H7C6.46957 21.0003 5.96086 20.7896 5.58579 20.4145C5.21071 20.0394 5 19.5307 5 19.0003V5.00029C5 4.46986 5.16309 4.00878 5.58579 3.58608C6.00849 3.16338 6.46957 3.00029 7 3.00029C7 3.00029 13.2471 2.99963 17.2499 3.00029C17.9334 3.00041 18.2509 3.14425 18.6412 3.58608C19.0814 4.08435 19 5.25029 19 5.25029V19.0003C19 19.5307 18.7893 20.0394 18.4142 20.4145C18.0391 20.7896 17.5304 21.0003 17 21.0003Z"
                fill="#023DA2"
                stroke="#023DA2"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M9 7.5H15"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M9 13H15"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
              <path
                d="M13 17H15"
                stroke="white"
                strokeWidth="1.5"
                strokeLinecap="round"
                strokeLinejoin="round"
              />
            </svg>
          </div>
          <span class="title">UploadFileIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 27 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M12 17.333h2.667V20H12v-2.667zm0-10.666h2.667v8H12v-8zM13.32 0C5.96 0 0 5.973 0 13.333s5.96 13.334 13.32 13.334c7.373 0 13.347-5.974 13.347-13.334C26.667 5.973 20.693 0 13.32 0zm.013 24C7.44 24 2.667 19.227 2.667 13.333c0-5.893 4.773-10.666 10.666-10.666C19.227 2.667 24 7.44 24 13.333 24 19.227 19.227 24 13.333 24z"
                fill="#fff"
              />
            </svg>
          </div>
          <span class="title">WarnCircleIcon</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              width="17"
              height="16"
              viewBox="0 0 17 16"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              ref="{svgRef}"
              {...props}
            >
              <path
                d="M16.6177 12.2605L10.6192 1.21735C10.1665 0.455191 9.36688 0 8.48035 0C7.59382 0 6.79422 0.455191 6.34148 1.21735C6.33807 1.22319 6.33519 1.22902 6.33178 1.23485L0.353201 12.243C-0.109245 13.0212 -0.117991 13.9558 0.329382 14.7428C0.777781 15.5303 1.5856 16 2.49157 16H14.436C15.342 16 16.183 15.5303 16.6314 14.7428C17.0787 13.9559 17.07 13.0212 16.6177 12.2605ZM7.48549 5.05643C7.48549 4.50696 7.93091 4.06157 8.48035 4.06157C9.02983 4.06157 9.47521 4.50699 9.47521 5.05643V9.03591C9.47521 9.58532 9.02979 10.0308 8.48035 10.0308C7.93091 10.0308 7.48549 9.58528 7.48549 9.03591V5.05643ZM8.48035 14.0103C7.65746 14.0103 6.98803 13.3409 6.98803 12.518C6.98803 11.6951 7.65743 11.0257 8.48035 11.0257C9.30324 11.0257 9.97264 11.6951 9.97264 12.518C9.97268 13.3408 9.30327 14.0103 8.48035 14.0103Z"
                fill="#E62C34"
              />
            </svg>
          </div>
          <span class="title">WarningIcon</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="16"
              height="16"
              fill="none"
              viewBox="0 0 16 16"
              ref="{svgRef}"
              {...props}
            >
              <path
                fillRule="evenodd"
                clipRule="evenodd"
                d="M3.40381 12.5962C0.865398 10.0578 0.865398 5.94221 3.40381 3.40381C5.94221 0.865398 10.0578 0.865398 12.5962 3.40381C15.1346 5.94221 15.1346 10.0578 12.5962 12.5962C10.0578 15.1346 5.94221 15.1346 3.40381 12.5962ZM2.34315 2.34315C-0.781049 5.46734 -0.781049 10.5327 2.34315 13.6569C5.46734 16.781 10.5327 16.781 13.6569 13.6569C16.781 10.5327 16.781 5.46734 13.6569 2.34315C10.5327 -0.781049 5.46734 -0.781049 2.34315 2.34315ZM6.03033 4.96967C5.73744 4.67678 5.26256 4.67678 4.96967 4.96967C4.67678 5.26256 4.67678 5.73744 4.96967 6.03033L6.93934 8L4.96967 9.96967C4.67678 10.2626 4.67678 10.7374 4.96967 11.0303C5.26256 11.3232 5.73744 11.3232 6.03033 11.0303L8 9.06066L9.96967 11.0303C10.2626 11.3232 10.7374 11.3232 11.0303 11.0303C11.3232 10.7374 11.3232 10.2626 11.0303 9.96967L9.06066 8L11.0303 6.03034C11.3232 5.73744 11.3232 5.26257 11.0303 4.96968C10.7374 4.67678 10.2626 4.67678 9.96967 4.96968L8 6.93934L6.03033 4.96967Z"
                fill="white"
              />
            </svg>
          </div>
          <span class="title">CancelCircle16Regular</span>
        </div>
        <div class="item">
          <div class="ico">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="16"
              height="16"
              fill="none"
              viewBox="0 0 16 16"
              ref="{svgRef}"
              {...props}
            >
              <path
                fill="currentcolor"
                fillRule="evenodd"
                d="M7.75 1a.75.75 0 01.75.75V7h5.25a.75.75 0 110 1.5H8.5v5.25a.75.75 0 11-1.5 0V8.5H1.75a.75.75 0 010-1.5H7V1.75A.75.75 0 017.75 1z"
                clipRule="evenodd"
              />
            </svg>
          </div>
          <span class="title">PlusMOutput</span>
        </div>
        <div class="item" style="background-color: lightgray">
          <div class="ico">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="16"
              height="16"
              fill="none"
              viewBox="0 0 16 16"
              ref="{svgRef}"
              {...props}
            >
              <path
                fillRule="evenodd"
                clipRule="evenodd"
                d="M0 1.5C0 0.671573 0.671573 0 1.5 0H10.3787C10.7765 0 11.158 0.158035 11.4393 0.43934L15.5607 4.56066C15.842 4.84197 16 5.2235 16 5.62132V14.5C16 15.3284 15.3284 16 14.5 16H1.5C0.671573 16 0 15.3284 0 14.5V1.5ZM1.5 2C1.5 1.72386 1.72386 1.5 2 1.5H9.79289C9.9255 1.5 10.0527 1.55268 10.1464 1.64645L14.3536 5.85355C14.4473 5.94732 14.5 6.0745 14.5 6.20711V14C14.5 14.2761 14.2761 14.5 14 14.5H12V10.5C12 9.67157 11.3284 9 10.5 9H5.5C4.67157 9 4 9.67157 4 10.5V14.5H2C1.72386 14.5 1.5 14.2761 1.5 14V2ZM5.5 14.5H10.5V11C10.5 10.7239 10.2761 10.5 10 10.5H6C5.72386 10.5 5.5 10.7239 5.5 11V14.5Z"
                fill="white"
              />
            </svg>
          </div>
          <span class="title">Save16Regular</span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
        <div class="item">
          <div class="ico"></div>
          <span class="title"></span>
        </div>
      </div>
    </div>
  </body>
</html>
