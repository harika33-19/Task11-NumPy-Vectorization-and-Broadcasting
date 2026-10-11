{

  "nbformat": 4,
  "nbformat_minor": 0,        
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "execution_count": 1,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "8gAwCes8gwFC",
        "outputId": "708146a8-a837-4f02-eb85-eb21f750c322"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "NumPy version: 2.1.3\n"
          ]
        }
      ],
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "print(\"NumPy version:\", np.__version__)\n"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "marks = np.array([70, 80, 90, 60, 85])\n",
        "print(\"Original marks:\", marks)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "p15cxDuFhQY7",
        "outputId": "5f4eb59c-ecaf-45f9-d0e8-85a4bef488bf"
      },
      "execution_count": 2,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Original marks: [70 80 90 60 85]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "marks = np.array([70, 80, 90, 60, 85])\n",
        "\n",
        "print(\"Addition:\", marks + 5)\n",
        "print(\"Subtraction:\", marks - 5)\n",
        "print(\"Multiplication:\", marks * 2)\n",
        "print(\"Division:\", marks / 2)\n",
        "print(\"Square:\", marks ** 2)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "MhPXFbg_hQTl",
        "outputId": "b8001ece-f783-4fbe-d670-4bc7e2d3899b"
      },
      "execution_count": 3,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Addition: [75 85 95 65 90]\n",
            "Subtraction: [65 75 85 55 80]\n",
            "Multiplication: [140 160 180 120 170]\n",
            "Division: [35.  40.  45.  30.  42.5]\n",
            "Square: [4900 6400 8100 3600 7225]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "arr = np.array([10, 20, 30, 40])\n",
        "\n",
        "result = arr + 5\n",
        "\n",
        "print(\"Original array:\", arr)\n",
        "print(\"After adding 5:\", result)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "eMaReeaFhQQC",
        "outputId": "8aaafd19-13e9-4838-91f2-17acd08f8f4a"
      },
      "execution_count": 4,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Original array: [10 20 30 40]\n",
            "After adding 5: [15 25 35 45]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "a = np.array([[10, 20, 30],\n",
        "              [40, 50, 60]])\n",
        "\n",
        "b = np.array([1, 2, 3])\n",
        "\n",
        "result = a + b\n",
        "\n",
        "print(result)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "dhcRGReRhQMV",
        "outputId": "4e555746-f6e8-4e3a-9704-7f03f9b9b691"
      },
      "execution_count": 5,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[11 22 33]\n",
            " [41 52 63]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "a = np.array([[10, 20, 30],\n",
        "              [40, 50, 60]])\n",
        "\n",
        "b = np.array([[1],\n",
        "              [2]])\n",
        "\n",
        "result = a + b\n",
        "\n",
        "print(result)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "aZqtF83AhQIj",
        "outputId": "efe9a3f5-8673-4358-b0b4-e984a2bd58fb"
      },
      "execution_count": 6,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[11 21 31]\n",
            " [42 52 62]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "prices = np.array([[100, 200, 300],\n",
        "                   [400, 500, 600]])\n",
        "\n",
        "discount = np.array([10, 20, 30])\n",
        "\n",
        "final_prices = prices - discount\n",
        "\n",
        "print(final_prices)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "BLzDVn5MhQEj",
        "outputId": "c001e9dd-edaa-4ccb-a316-6f938aee9e43"
      },
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[ 90 180 270]\n",
            " [390 480 570]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "marks = [70, 80, 90, 60, 85]\n",
        "\n",
        "result = []\n",
        "\n",
        "for mark in marks:\n",
        "    result.append(mark + 5)\n",
        "\n",
        "print(result)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "64r_-dQWhmM9",
        "outputId": "7037ef7a-f63c-456c-9637-de579839ec96"
      },
      "execution_count": 8,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[75, 85, 95, 65, 90]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "marks = np.array([70, 80, 90, 60, 85])\n",
        "\n",
        "result = marks + 5\n",
        "\n",
        "print(result)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "bcE4294xhoZ3",
        "outputId": "d21b30bc-aec1-4c0f-b312-846589b38979"
      },
      "execution_count": 9,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[75 85 95 65 90]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "import numpy as np\n",
        "\n",
        "students = np.array([\"Ravi\", \"Sita\", \"Arun\", \"Priya\"])\n",
        "marks = np.array([70, 85, 60, 95])\n",
        "\n",
        "# Add 5 bonus marks\n",
        "updated_marks = marks + 5\n",
        "\n",
        "# Calculate percentage out of 100\n",
        "percentage = updated_marks / 100 * 100\n",
        "\n",
        "# Find students who scored 75 or above\n",
        "passed = updated_marks >= 75\n",
        "\n",
        "print(\"Students:\", students)\n",
        "print(\"Updated marks:\", updated_marks)\n",
        "print(\"Percentage:\", percentage)\n",
        "print(\"Scored 75 or above:\", passed)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "CWrelE4RhoWZ",
        "outputId": "6ebd0981-c313-4835-c8c7-2c3e4fce0ff0"
      },
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Students: ['Ravi' 'Sita' 'Arun' 'Priya']\n",
            "Updated marks: [ 75  90  65 100]\n",
            "Percentage: [ 75.  90.  65. 100.]\n",
            "Scored 75 or above: [ True  True False  True]\n"
          ]
        }
      ]
    }
  ]
}
