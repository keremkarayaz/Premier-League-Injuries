# Premier League Injury Analysis Dashboard

This project provides an in-depth analysis of injury trends and FIFA ratings for Premier League teams using Power BI. The dashboard is designed to help visualize injury patterns, recovery times, and player statistics over different seasons.

---

## 📊 Features

- **Injury Data:**
  - Total number of hamstring injuries and other types of injuries.
  - Average age of injured players.
  - Longest recovery times for all injuries.
  - Most injured player: *Giovani Lo Celso*.

- **Team Analysis:**
  - FIFA average ratings by team.
  - Injury count by player position.
  - Average age of players by position.

- **Seasonal Trends:**
  - Injury counts across the 2019/20 to 2023/24 seasons.

---

## 🚀 How to Use

1. Clone this repository or download the `.pbix` file.
2. Open the `Premier Ligue.pbix` file in Power BI Desktop.
3. Explore the visualizations and interact with the slicers to focus on specific teams, seasons, or positions.

---

## 📂 Repository Structure

- **`Premier Ligue.pbix`**: The Power BI dashboard file.
- **`/Measures/`**: Folder containing DAX measure formulas used in the dashboard.
  - Example measure: 
    ```dax
    // Total Hamstring Injuries
    COUNTROWS(FILTER(Injuries, Injuries[Type] = "Hamstring"))
    ```

---

## 🛠️ Tools Used

- **Power BI Desktop**: For creating the dashboard.
- **DAX Studio**: To extract and manage DAX measures.
- **Premier League Dataset**: Includes injury details, player statistics, and team information.

---

## 📌 Insights

- Teams with higher FIFA average ratings generally report fewer injuries.
- Certain positions, such as left-backs and central midfielders, experience more injuries.
- The most injury-prone player over the analyzed seasons is *Giovani Lo Celso*.

---

## 📥 Download and Installation

1. Ensure you have Power BI Desktop installed.
2. Download the `.pbix` file from this repository.
3. Open the file to start analyzing.

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

### Contributions

Feel free to open issues or submit pull requests for improving the analysis or expanding the dataset.

---


