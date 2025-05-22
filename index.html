<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galante 5期目 組織図 (印刷最適化版)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Base styling for the body and overall chart container */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f4f8; /* Light blue-gray background */
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 1rem; /* Reduced padding */
            color: #333;
        }

        /* Main container for the organization chart */
        .org-chart {
            background-color: #ffffff;
            border-radius: 1.5rem; /* More rounded corners */
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1); /* Stronger shadow */
            padding: 1.5rem; /* Reduced padding */
            max-width: 1200px;
            width: 100%;
            overflow-x: auto; /* Allow horizontal scrolling on small screens */
        }

        /* Styling for unordered lists (tree branches) */
        .org-chart ul {
            padding-left: 0;
            list-style: none;
            text-align: center;
            position: relative;
            margin: 0;
        }

        /* Styling for list items (individual nodes/roles) */
        .org-chart ul li {
            display: inline-block;
            vertical-align: top;
            padding: 1rem 0.25rem; /* Reduced vertical padding */
            position: relative;
            margin: 0 0.5rem; /* Reduced spacing between siblings */
        }

        /* Connectors for the tree structure (lines between nodes) */
        .org-chart ul li::before,
        .org-chart ul li::after {
            content: '';
            position: absolute;
            top: 0;
            right: 50%;
            border-top: 2px solid #6366f1; /* Indigo 500 */
            width: 50%;
            height: 1rem; /* Reduced height of vertical line */
        }

        .org-chart ul li::after {
            right: auto;
            left: 50%;
            border-left: 2px solid #6366f1;
        }

        /* Hide connectors for single child nodes */
        .org-chart ul li:only-child::after,
        .org-chart ul li:only-child::before {
            display: none;
        }

        /* Adjust padding for single child nodes */
        .org-chart ul li:only-child {
            padding-top: 0;
        }

        /* Remove specific borders for first/last child nodes to create clean corners */
        .org-chart ul li:first-child::before,
        .org-chart ul li:last-child::after {
            border: 0 none;
        }

        /* Apply border-radius for corner connections */
        .org-chart ul li:last-child::before {
            border-right: 2px solid #6366f1;
            border-radius: 0 5px 0 0;
            -webkit-border-radius: 0 5px 0 0;
            -moz-border-radius: 0 5px 0 0;
        }

        .org-chart ul li:first-child::after {
            border-radius: 5px 0 0 0;
            -webkit-border-radius: 5px 0 0 0;
            -moz-border-radius: 5px 0 0 0;
        }

        /* Vertical connector from parent to children list */
        .org-chart ul ul::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            border-left: 2px solid #6366f1;
            width: 0;
            height: 1rem; /* Reduced height of vertical line to parent */
        }

        /* Styling for individual node boxes */
        .org-chart ul li .node {
            padding: 0.5rem 0.75rem; /* Reduced padding for content */
            border: 1px solid #a78bfa; /* Purple 300 */
            background-color: #ede9fe; /* Purple 100 */
            border-radius: 0.75rem; /* Rounded corners for nodes */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08); /* Node specific shadow */
            display: inline-block;
            min-width: 150px; /* Reduced min width */
            max-width: 220px; /* Reduced max width */
            text-align: left;
            transition: all 0.3s ease;
            cursor: default;
        }

        /* Hover effect for nodes */
        .org-chart ul li .node:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.12);
        }

        /* Text styling within nodes */
        .org-chart .role {
            font-weight: 600; /* Semibold */
            color: #4c1d95; /* Deep purple for roles */
            font-size: 0.85rem; /* Reduced font size */
            margin-bottom: 0.15rem; /* Reduced margin */
        }

        .org-chart .name {
            font-size: 0.75rem; /* Reduced font size */
            color: #6b7280; /* Gray 500 */
            margin-bottom: 0.25rem; /* Reduced margin */
        }

        .org-chart .responsibility {
            font-size: 0.65rem; /* Reduced font size */
            color: #4b5563; /* Gray 600 */
            line-height: 1.2; /* Reduced line height */
            max-height: 2.6em; /* Limit height to 2 lines (approx) */
            overflow: hidden;
            text-overflow: ellipsis;
            display: -webkit-box;
            -webkit-line-clamp: 2; /* Limit to 2 lines */
            -webkit-box-orient: vertical;
        }

        /* Specific styling for external support nodes */
        .org-chart .external-support .node {
            background-color: #e0f2f7; /* Light cyan for external */
            border-color: #81d4fa; /* Light blue for external */
        }
        .org-chart .external-support .role,
        .org-chart .external-support .name,
        .org-chart .external-support .responsibility {
            color: #00838f; /* Darker cyan */
        }

        /* Responsive adjustments for smaller screens */
        @media (max-width: 768px) {
            .org-chart ul li {
                display: block;
                padding: 0.5rem 0; /* Further reduced padding */
                margin: 0;
                text-align: left;
            }

            .org-chart ul li::before,
            .org-chart ul li::after {
                display: none; /* Hide horizontal connectors for vertical stack */
            }

            .org-chart ul ul::before {
                left: 0.75rem; /* Align vertical line to the left */
                height: 0.75rem;
            }

            .org-chart ul li .node {
                margin-left: 1.5rem; /* Indent child nodes */
                width: calc(100% - 1.5rem);
                min-width: unset;
                max-width: unset;
            }

            .org-chart ul ul {
                padding-left: 0;
            }
        }

        /* ==================================================================== */
        /* PRINT-SPECIFIC STYLES */
        /* ==================================================================== */
        @media print {
            body {
                margin: 0 !important;
                padding: 0 !important;
                background-color: #fff !important; /* White background for print */
                -webkit-print-color-adjust: exact; /* Ensure background colors are printed if desired */
                color-adjust: exact;
            }
            .org-chart {
                box-shadow: none !important;
                padding: 0.5rem !important; /* Reduced padding for print */
                overflow-x: visible !important; /* Ensure content is fully visible, not scrolled */
                width: auto !important; /* Allow width to expand if needed */
                max-width: unset !important; /* Remove max-width for print */
                background-color: #fff !important; /* Ensure white background for print */
                border-radius: 0 !important; /* No rounded corners on print */
            }
            .org-chart h2 {
                margin-top: 0.5rem !important;
                margin-bottom: 0.75rem !important;
                font-size: 1.2rem !important; /* Smaller title on print */
                color: #000 !important; /* Black for print */
            }
            .org-chart ul {
                text-align: center !important;
                page-break-inside: avoid; /* Try to keep ul together */
            }
            .org-chart ul li {
                padding: 0.5rem 0.1rem !important; /* Further reduced padding for print nodes */
                margin: 0 0.2rem !important; /* Further reduced spacing */
                page-break-inside: avoid; /* Try to keep li together */
            }
            .org-chart ul li .node {
                background-color: #fff !important; /* White background for print */
                border-color: #aaa !important; /* Lighter border for print */
                box-shadow: none !important; /* No shadows on print */
                min-width: 100px !important; /* Smaller min-width for print */
                max-width: 180px !important; /* Smaller max-width for print */
                padding: 0.2rem 0.3rem !important; /* Minimal padding for print */
            }
            .org-chart .role {
                font-size: 0.7rem !important; /* Smaller on print */
                color: #000 !important; /* Black for print */
                margin-bottom: 0.1rem !important;
            }
            .org-chart .name {
                font-size: 0.6rem !important; /* Smaller on print */
                color: #333 !important;
                margin-bottom: 0.1rem !important;
            }
            .org-chart .responsibility {
                font-size: 0.55rem !important; /* Smaller on print */
                color: #555 !important;
                line-height: 1.1 !important; /* Tighter line height */
                max-height: unset !important; /* Allow all lines to show */
                -webkit-line-clamp: unset !important; /* Disable line clamping */
            }
            .org-chart ul li::before,
            .org-chart ul li::after,
            .org-chart ul ul::before {
                border-color: #666 !important; /* Darker lines for print */
                border-width: 1px !important; /* Thinner lines */
            }
            .org-chart ul li:last-child::before,
            .org-chart ul li:first-child::after {
                border-radius: 0 !important; /* No rounded corners on print lines */
                -webkit-border-radius: 0 !important;
                -moz-border-radius: 0 !important;
            }
            /* Specific styling for external support nodes on print */
            .org-chart .external-support .node {
                background-color: #f0f0f0 !important; /* Light gray for distinction */
                border-color: #bbb !important;
            }
            .org-chart .external-support .role,
            .org-chart .external-support .name,
            .org-chart .external-support .responsibility {
                color: #333 !important;
            }
        }
    </style>
</head>
<body>
    <div class="org-chart">
        <h2 class="text-3xl font-bold text-center mb-8 text-indigo-700">Galante 5期目 組織図</h2>

        <ul>
            <li>
                <div class="node">
                    <div class="role">CEO</div>
                    <div class="name">甲斐 龍之介</div>
                    <div class="responsibility">最終意思決定・組織戦略、全社ビジョン・文化設計、事業開発、組織設計・調整、人員配置・役割設計、各部門の実行支援と仕組み化</div>
                </div>
                <ul>
                    <li>
                        <div class="node">
                            <div class="role">新規事業チーム (将来的な構想)</div>
                            <div class="responsibility">人材紹介、SOCIAL RECRUIT（HR SaaS）</div>
                        </div>
                    </li>
                    <li>
                        <div class="node external-support">
                            <div class="role">営業コンサル (Sales Development 局全体)</div>
                            <div class="name">佐藤 晃一</div>
                            <div class="responsibility">数字管理・分析／ボトルネック抽出／改善施策考案／会議ファシリ・施策実装／仕組み作り</div>
                        </div>
                    </li>
                    <li>
                        <div class="node">
                            <div class="role">Sales Development 局</div>
                            <div class="responsibility">営業戦略の再構築と数値分解、マーケティング領域商材での売上構築</div>
                        </div>
                        <ul>
                            <li>
                                <div class="node">
                                    <div class="role">営業締結責任者</div>
                                    <div class="name">高橋 慧</div>
                                    <div class="responsibility">契約件数／商談成果／文化営業の体現・浸透／0→1を1→15にする実現化（アポを受注へ）</div>
                                </div>
                            </li>
                            <li>
                                <div class="node">
                                    <div class="role">新規開拓責任者</div>
                                    <div class="name">森川 遼</div>
                                    <div class="responsibility">0→1新規開拓創出／営業組織マネジメント／日々の数字管理／KPI運用／営業機会の創出</div>
                                </div>
                                <ul>
                                    <li>
                                        <div class="node">
                                            <div class="role">営業メンバー (マーケ兼務)</div>
                                            <div class="name">梅本</div>
                                            <div class="responsibility">リスト作成／コール数／アポ取得率／新規営業数／初回商談率／契約率</div>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="node">
                                            <div class="role">営業メンバー (マーケ兼務)</div>
                                            <div class="name">山本</div>
                                            <div class="responsibility">リスト作成／コール数／アポ取得率／新規営業数／初回商談率／契約率</div>
                                        </div>
                                    </li>
                                </ul>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <div class="node">
                            <div class="role">Business Produce 局</div>
                            <div class="responsibility">マーケ／PM・品質・進行・納品管理責任、商品定義／単価設計／原価率管理／商談可否判断／品質管理／営業・提供の橋渡し／再受注創出／プランニング</div>
                        </div>
                        <ul>
                            <li>
                                <div class="node">
                                    <div class="role">商品品質責任者 (内部寄り)</div>
                                    <div class="name">阿久津 哲秀</div>
                                    <div class="responsibility">商品定義／単価設計／原価率管理／商談可否判断／品質管理／営業・提供の橋渡し／再受注創出</div>
                                </div>
                            </li>
                            <li>
                                <div class="node">
                                    <div class="role">進行調整責任者 (営業寄り)</div>
                                    <div class="name">齋 克弥</div>
                                    <div class="responsibility">提供する商品の調整：いくらで・何を・いつまでに 仕切りと握り ※窓口で営業寄りにてご紹介創出</div>
                                </div>
                            </li>
                            <li>
                                <div class="node">
                                    <div class="role">PM/マーケティングチーム</div>
                                    <div class="responsibility">PM補佐、マーケティングメンバー、外部スタッフの統括</div>
                                </div>
                                <ul>
                                    <li>
                                        <div class="node">
                                            <div class="role">PM補佐 (PM兼BO)</div>
                                            <div class="name">村松 奈央</div>
                                            <div class="responsibility">プロジェクト整理／処理遅延ゼロ／納品物品質・納期管理／再受注創出</div>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="node">
                                            <div class="role">マーケティングメンバー</div>
                                            <div class="name">宮川</div>
                                            <div class="responsibility">PMアシスタント／プランニング／取り扱い案件数／キャスティング数／案件品質・納期管理</div>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="node external-support">
                                            <div class="role">マーケティングメンバー (外部)</div>
                                            <div class="name">関</div>
                                            <div class="responsibility">アカウント運用代行におけるPM／案件品質・納期管理／再受注創出</div>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="node">
                                            <div class="role">マーケティングメンバー (兼務)</div>
                                            <div class="name">梅本</div>
                                            <div class="responsibility">取り扱い案件数／キャスティング数／案件品質・納期管理</div>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="node">
                                            <div class="role">マーケティングメンバー (兼務)</div>
                                            <div class="name">山本</div>
                                            <div class="responsibility">取り扱い案件数／キャスティング数／案件品質・納期管理</div>
                                        </div>
                                    </li>
                                </ul>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <div class="node">
                            <div class="role">管理・バックオフィス</div>
                            <div class="responsibility">経理・総務、請求締め完了率／社内最適化</div>
                        </div>
                        <ul>
                            <li>
                                <div class="node">
                                    <div class="role">経理・総務 (兼務)</div>
                                    <div class="name">村松 奈央</div>
                                    <div class="responsibility">請求締め完了率／社内最適化</div>
                                </div>
                            </li>
                            <li>
                                <div class="node external-support">
                                    <div class="role">財務 (外部)</div>
                                    <div class="name">徳永</div>
                                    <div class="responsibility">資金繰り／予実乖離管理</div>
                                </div>
                            </li>
                            <li>
                                <div class="node external-support">
                                    <div class="role">労務 (外部)</div>
                                    <div class="name">中村</div>
                                    <div class="responsibility">勤怠処理精度／対応速度</div>
                                </div>
                            </li>
                            <li>
                                <div class="node external-support">
                                    <div class="role">経理 (外部)</div>
                                    <div class="name">FA</div>
                                    <div class="responsibility">税務処理／月次処理対応スピード／月次・四半期・年次決算</div>
                                </div>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <div class="node">
                            <div class="role">法務顧問</div>
                            <div class="name">鮎川</div>
                            <div class="responsibility">法務リスク／トラブル回避／契約関連</div>
                        </div>
                        <ul>
                            <li>
                                <div class="node external-support">
                                    <div class="role">法務関連スタッフ (外部)</div>
                                    <div class="responsibility">法務リスク／トラブル回避／契約関連</div>
                                </div>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <div class="node">
                            <div class="role">人事／採用</div>
                            <div class="name">村松 奈央 (兼務) + 甲斐</div>
                            <div class="responsibility">Galanteカルチャーにマッチした人材獲得／GalanteShipに則った人事評価、採用計画／求人媒体管理／面接日程調整、オンボーディング運用、評価制度設計／運用／評価者ガイド整備</div>
                        </div>
                        <ul>
                            <li>
                                <div class="node external-support">
                                    <div class="role">組織コンサル (外部)</div>
                                    <div class="name">佐藤 晃一</div>
                                    <div class="responsibility">組織の円滑化</div>
                                </div>
                            </li>
                        </ul>
                    </li>
                </ul>
            </li>
        </ul>
    </div>
</body>
</html>
