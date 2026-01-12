#include <bits/stdc++.h>
using namespace std;

int main() {
    ios::sync_with_stdio(false);
    cin.tie(NULL);

    int t;
    cin >> t;

    while (t--) {
        int n, k;
        cin >> n >> k;

        vector<long long> arr(n);
        for (int i = 0; i < n; i++) {
            cin >> arr[i];
        }

        // If k == 1, array must already be sorted
        if (k == 1) {
            bool sorted = true;
            for (int i = 1; i < n; i++) {
                if (arr[i] < arr[i - 1]) {
                    sorted = false;
                    break;
                }
            }

            if (sorted)
                cout << "YES\n";
            else
                cout << "NO\n";
        }
        // If k >= 2, always possible
        else {
            cout << "YES\n";
        }
    }

    return 0;
}
